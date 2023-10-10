---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: Python
          description: 80%
          icon: python
          icon_pack: fab
        - name: Statistics
          description: 80%
          icon: chart-line
          icon_pack: fas

        - name: LOL
          description: Gold
          icon: LOL
          icon_pack: custom
  - block: experience
    id: Experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Internship
          company: Shengli Oilfield, Sinopec
          company_url: ''
          company_logo: 
          location: Dongying, Shandong
          date_start: '2022-08-01'
          date_end: '2023-03-01'
          description: |2-
              Responsibilities include:

              * Data processing
              * Data analysis
        - title: Professor of Semiconductor Physics
          company: CITIC Securities
          company_url: ''
          company_logo: 
          location: Shanghai
          date_start: '2023-07-01'
          date_end: '2023-08-01'
          description: System Operation and Maintenance.

    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.


    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    id: Gallery
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo2" >}}

    design:
      columns: '2'
      view: card
  - block: collection
    id: Publications
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true

    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: yxzhou@ir.hit.edu.cn
      phone: 17601555947
      appointment_url: 'https://calendly.com'
      address:
        street: 海淀区银桦路58号院2号楼
        city: 北京市
        postcode: '100086'
        country: 中国
        country_code: CN
      office_hours:
        - '8:00 to 22:00'
      contact_links:
        - icon: weixin
          icon_pack: fab
          name: zyx_alter

      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
