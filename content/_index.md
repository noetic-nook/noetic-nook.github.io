---
title: 'Home'
date: 2023-10-24
type: landing
share: true

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Noetic Nook
      text: A simply creative company
      # primary_action:
      #   text: Get Started
      #   url: https://hugoblox.com/templates/
      #   icon: rocket-launch
      # secondary_action:
      #   text: Read the docs
      #   url: https://docs.hugoblox.com
      announcement:
        text: " "
        link:
          text: "Announcing the release of Children's Books"
          url: "https://www.amazon.com/author/parveen.minocha"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
  # - block: stats
    # content:
    #   items:
    #     - statistic: "1M+"
    #       description: |
    #         Websites built  
    #         with Hugo Blox
    #     - statistic: "10k+"
    #       description: |
    #         GitHub stars  
    #         since 2016
    #     - statistic: "3k+"
    #       description: |
    #         Discord community  
    #         for support
    # design:
    #   # Section background color (CSS class)
    #   css_class: "bg-gray-100 dark:bg-gray-900"
    #   # Reduce spacing
    #   spacing:
    #     padding: ["1rem", 0, "1rem", 0]
  # - block: features
  #   id: features
  #   content:
  #     title: Features
  #     text: Build your site with blocks 🧱
  #     items:
  #       - name: Optimized SEO
  #         icon: magnifying-glass
  #         description: Automatic sitemaps, RSS feeds, and rich metadata take the pain out of SEO and syndication.
  #       - name: Fast
  #         icon: bolt
  #         description: Super fast page load with Tailwind CSS and super fast site building with Hugo.
  #       - name: Easy
  #         icon: sparkles
  #         description: One-click deployment to GitHub Pages. Have your new website live within 5 minutes!
  #       - name: No-Code
  #         icon: code-bracket
  #         description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
  #       - name: Highly Rated
  #         icon: star
  #         description: Rated 5-stars by the community.
  #       - name: Swappable Blocks
  #         icon: rectangle-group
  #         description: Build your pages with blocks - no coding required!
  - block: cta-image-paragraph
    id: book
    content:
      items:
        - title: Books
          id: book
          text: Collection of children's books
          feature_icon: bolt
          features:
            - "Chumbak: nanhe-munno ke liye kavitaayein"
            - "Madhuban: Sundar Pashu-Pakshi Es Dharti Par"
            - "My First OM"
          # Upload image to `assets/media/` and reference the filename here
          image: noeticnook-book.png
          button:
            text: Buy Now
            url: https://www.amazon.com/author/parveen.minocha
        - title: Poems
          id: poem
          text: For your intellect
          feature_icon: check
          features:
            - "Hindi Ki Bindi"
            - "The Artic Cold"
            - "Poetry-Doha Jugalbandi"
          # Upload image to `assets/media/` and reference the filename here
          image: noeticnook-poem.png
          button:
            text: Watch More
            url: https://www.youtube.com/@noeticnook
        - title: Songs
          id: song
          text: Coming Soon
          feature_icon: bolt
          features:
            - "Mann Ke Andar"
            - "Teri Yaad"
            # - "...."
          # Upload image to `assets/media/` and reference the filename here
          image: noeticnook-songs.png
          # button:
          #   text: Coming Soon
            # url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Garima Chotani"
          role: "Marketing Executive at X"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: "Great phonics book to teach animal sounds for the new generation kids who are living in the age of Hindi, English and Hinglish (Hindi written in English). The book has cute illustrations too! It is a great hit with my 3 year old nephew. Would recommend this book as a fun way to introduce Hindi and English translations to your child."
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  # - block: cta-card
  #   content:
  #     title: Build your future-proof website
  #     text: As easy as 1, 2, 3!
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: "bg-primary-700"
  #       css_style: ""

  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: Checkout collection of children’s books
          icon: custom/amazon
          url: https://www.amazon.com/author/parveen.minocha
        - text: Watch poems for intellect
          icon: brands/youtube
          url: https://youtube.com
        # - text: Connect with me on LinkedIn
        #   icon: brands/linkedin
        #   url: https://linkedin.com
---
