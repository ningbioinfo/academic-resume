---
title: null
date: 2023-04-10T00:00:00.000Z
type: landing
sections:
  - block: about.avatar
    id: about
    content:
      username: admin
      text: null
  - block: features
    content:
      title: Skills
      items:
        - name: R
          description: Bioconductor developer
          icon: r-project
          icon_pack: fab
        - name: Python
          description: Data processing
          icon: python
          icon_pack: fab
        - name: Bash/C++
          description: Daily use
          icon: code
          icon_pack: fas
  - block: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: Research Officer
          company: Walter & Eliza Hall Institute
          company_url: ''
          company_logo: null
          location: 'Melbourne, Australia'
          date_start: '2021-05-01'
          date_end: '2024-01-03'
          description: |2-
              Responsibilities include:

              * Analysing data
              * Modelling biological questions
              * Deploying software packages
              * Writing research articles
        - title: Post doc
          company: University of Adelaide
          company_url: ''
          company_logo: null
          location: 'Adelaide, Australia'
          date_start: '2023-01-03'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Analysing data
              * Modelling biological questions
              * Deploying software packages
              * Writing research articles      
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      default_button_index: 0
      buttons:
        - name: All
          tag: '*'
        - name: Spatial
          tag: Spatial
        - name: Other
          tag: Other
    design:
      columns: '1'
      view: showcase
      flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: '{{< gallery album="demo" >}}'
    design:
      columns: '1'
  - block: collection
    content:
      title: Recent Publications
      text: >-
        {{% callout note %}}

        Quickly discover relevant content by [filtering
        publications](./publication/).

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
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: null
      text: >-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam,
        venenatis ut magna et, vehicula efficitur enim.
      email: test@example.org
      phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
      autolink: true
      form:
        provider: netlify
        formspree:
          id: null
        netlify:
          captcha: false
    design:
      columns: '2'
---
