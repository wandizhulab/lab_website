---
# Page title
title: Research
# Page type - we want a landing page (such as a homepage)
type: landing

# Your landing page sections - add as many different content blocks as you like
sections:
  # A section to display blog posts
  - block: collection
    id: section-1
    content:
      title: Research Overview
      #subtitle: A subtitle
      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
      # Display content from the `content/post/` folder
      filters:
        folders:
          - research
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose your content listing view - here we use the `showcase` view
      view: showcase
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: true
---


<!-- ---
title: Research

# Listing view
view: compact

# Optional banner image (relative to `assets/media/` folder).
banner:
  caption: ''
  image: ''
--- -->
