---
title: General enquiries
sections:
  - type: hero_section
    title: Contact
    subtitle: '"If you gaze long into an abyss, the abyss also gazes into you"'
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: >
      ### Woah, slow down Dorothy


      If you want my help taking other people’s money, I want to know more about
      you first.


      I want to know if I like you and if I can work with you. Unless you’re
      selling arsenic disguised as children’s food, I don’t care that much about
      your product - well I do, but it’s not the most important thing.


      Let me know about yourself, your project, why you want to do it and how
      you imagine me contributing to it. I will do my best to reply within 48
      hours.


      Thank you!
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: inline
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Error on the site
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
layout: advanced
---
