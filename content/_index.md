---
date: "2022-10-24"
sections:

- block: about.avatar
  content:
    text: null
    username: admin
  id: about
- block: features
  content:
    items:
    - description: 
      icon: r-project
      icon_pack: fab
      name: R
    - description: 
      icon: python
      icon_pack: fab
      name: Python
    - description: 
      icon: earth-americas
      icon_pack: fas
      name: GIS
    - description: 
      icon: chart-line
      icon_pack: fas
      name: Statistics
    - description: 
      icon: database
      icon_pack: fa
      name: Databases
    - description: 
      icon: pie-chart
      icon_pack: fa
      name: Data Visualization
    - description: 
      icon: aws
      icon_pack: fab
      name: Cloud Computing
    - description: 
      icon: brain
      icon_pack: fas
      name: Machine Learning
    - description: 
      icon: docker
      icon_pack: fab
      name: Docker
    title: Skills
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: Hitachi Ltd, Japan
      company_url: ""
      date_end: "2022-07-15"
      date_start: "2016-05-01"
      description: |2-
          Responsibilities include:

          * Led a team of 5 members in data collection and analysis for the JICA funded project. 
          * Modelling
          * Deploying
      location: India
      title: ITS Consultant
    - company: a'XYkno Capital Services Pvt Ltd
      company_url: ""
      date_end: "2022-07-15"
      date_start: "2015-10-01"
      description: Taught electronic engineering and researched semiconductor physics.
      location: India
      title: Assistant General Manager
    title: Experience
  design:
    columns: "2"
- block: accomplishments
  content:
    date_format: Jan 2006
    items:
    - certificate_url: https://www.coursera.org
      date_end: ""
      date_start: "2021-01-25"
      description: ""
      organization: Coursera
      organization_url: https://www.coursera.org
      title: Neural Networks and Deep Learning
      url: ""
    - certificate_url: https://www.edx.org
      date_end: ""
      date_start: "2021-01-01"
      description: Formulated informed blockchain models, hypotheses, and use cases.
      organization: edX
      organization_url: https://www.edx.org
      title: Blockchain Fundamentals
      url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
    - certificate_url: https://www.datacamp.com
      date_end: "2020-12-21"
      date_start: "2020-07-01"
      description: ""
      organization: DataCamp
      organization_url: https://www.datacamp.com
      title: Object-Oriented Programming in R
      url: ""
    subtitle: null
    title: Accomplish&shy;ments
  design:
    columns: "2"
- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Recent Posts
  design:
    columns: "2"
    view: compact
  id: posts
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Deep Learning
      tag: Deep Learning
    - name: Other
      tag: Demo
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
- block: markdown
  content:
    subtitle: ""
    text: '{{< gallery album="demo" >}}'
    title: Gallery
  design:
    columns: "1"
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: "2"
    view: card
  id: featured
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Recent Publications
  design:
    columns: "2"
    view: citation
- block: collection
  content:
    filters:
      folders:
      - event
    title: Recent & Upcoming Talks
  design:
    columns: "2"
    view: compact
  id: talks
- block: tag_cloud
  content:
    title: Popular Topics
  design:
    columns: "2"
title: null
type: landing
---
