---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: ברוכים הבאים
      image:
        filename: hero-academic.png
      text: |-
        זה אתר אור בהירות הדרך כאן תבינו מה רוצים ממכם
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true

  - block: collection
    id: posts
    content:
      title: תוכן עניינים של האתר 1
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - trains
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: תוכן עניינים של האתר 2
      filters:
        folders:
          - trains
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: הכל
          tag: '*'
        - name: פולין
          tag: פולין
        - name: הונגריה
          tag: הונגריה
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: featured
    content:
      title: תוכן עניינים של האתר 3
      filters:
        folders:
          - trains
    design:
      columns: '2'
      view: card
  - block: tag_cloud
    content:
      title: תגיות
    design:
      columns: '2'
  
---
