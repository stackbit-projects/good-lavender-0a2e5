---
title: Contact
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: |
      Para contactarme, completa el siguiente formulario por favor. 
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nombre
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Correo electrónico
        default_value: Your email address
        is_required: true
      - input_type: select
        name: subject
        label: Asunto
        default_value: Please select
        options:
          - Me interesa contactarte
          - Agradecimiento
          - Otro
      - input_type: textarea
        name: message
        label: Mensaje
        default_value: Your message
    submit_label: Send Message
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
