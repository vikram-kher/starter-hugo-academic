---
# Leave the homepage title empty to use the site title
title: Vikram Kher
date: 2022-10-24
type: landing

sections:
  - block: v1/about
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: collection
    id: publications
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        [Filter Publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # text: |-
      #  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: vikram [dot] kher [at] yale [dot] edu
      address:
        street: Arthur K. Watson Hall, 51 Prospect Street
        city: New Haven
        region: CT
        postcode: '06511'
        country: United States
        country_code: US
    design:
      columns: '2'
---
