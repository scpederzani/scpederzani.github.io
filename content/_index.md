---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: particles_dark.jpg
          placement: 3
          filters:
            brightness: 1.0
          position: center
          parallax: false
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: papers
    content:
      title: Ongoing Projects
      filters:
        folders:
          - project
        featured_only: true
    design:
      view: article-grid
      columns: 1
   - block: contact
    id: contact
    content:
      title: 🏫 Contact
      subtitle:
      text: |-

  #   # Contact (add or remove contact options as necessary)
      email: sarah.pederzani@utah.edu
  #     # phone: 
  #     # appointment_url: 
      address:
        # street: 115 S 1460 E FASB
        city: Salt Lake City
        region: Utah
        postcode: '84112'
        country: USA
        # country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      # autolink: true
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
  - block: markdown
    content:
      title:
      subtitle:
      text: |

        # <div style="width: 100%; height: auto;">
        <script type="text/javascript" src="//rf.revolvermaps.com/0/0/6.js?i=5nkevw8m6m7&amp;m=0&amp;c=ff0000&amp;cr1=ffffff&amp;f=arial&amp;l=0" async="async"></script>
        # </div>
    design:
      columns: '1'
      background:
        image:
          filename: 
---
