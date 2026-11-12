---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        My research examines how law and ethics shape patient autonomy and end-of-life decision-making, drawing on comparative analysis of China, South Korea, the United States, the United Kingdom and Germany. Current themes include advance directives and healthcare proxy decision-making, end-of-life care infrastructure and health equity, and the regulatory governance of telemedicine.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - events
    design:
      view: card
      show_date: false
  - block: collection
    id: news
    content:
      title: News
      subtitle: ''
      text: ''
      page_type: blog
      count: 10
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0
      order: desc
    design:
      view: card
      show_date: false
      show_read_time: false
      spacing:
        padding: [0, 0, 0, 0]
---