---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        Please don't hesitate to get in touch if you're interested in volunteering for one of our studies, collaborating on a research project or simply curious about our work!
      email: mrs@kcl.ac.uk
      #phone: 888 888 88 88
      address:
        street: 16 De Crespigny Park
        city: London
        #region: CA
        postcode: 'SE5 8AF'
        country: United Kingdom
        country_code: UK
      coordinates:
        latitude: '51.470852555813394'
        longitude: '-0.08945856931084234'
      directions: Department of Forensic and Neurodevelopmental Sciences, IoPPN Main Building (Floor 1)
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      #appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
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
          filename: IoPPN.jpg
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
