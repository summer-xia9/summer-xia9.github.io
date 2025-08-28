---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        电能源化学与先进储能材料团队
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        &emsp;&emsp;团队聚焦世界科技前沿，瞄准国家战略和企业需求，长期致力于能源电化学与储能器件的应用基础研究，包括锂/钠离子电池、水系电池、锂空电池、超级电容器等储能器件设计及新型储能电极材料、电解液/固态电解质等关键组分开发。
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  
  - block: collection
    content:
      title: 最新研究进展
      text: ""
      count: 4
      filters:
        folders:
          - publication
        publication_type: article-journal
    design:
      view: compact
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
