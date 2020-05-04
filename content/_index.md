---
title: Home
sections:
- type: heroblock
  template: heroblock
  title: Hi, I'm Stackbit Exto Portfolio Theme.
  section_id: hero
  component: hero_block.html
  content: This section can contain a subtitle or tagline. The recommended length
    is one to three sentences, but can be changed as you prefer.
- type: portfolioblock
  template: portfolioblock
  title: Recent Work
  section_id: latest-projects
  component: portfolio_block.html
  subtitle: An optional subtitle of the section
  layout_style: mosaic
  num_projects_displayed: 6
  view_all_text: View All
  view_all_url: portfolio/index.html
- type: servicesblock
  template: servicesblock
  title: Áreas de atuação
  section_id: services
  component: services_block.html
  subtitle: Áreas em que atuamos.
  serviceslist:
  - title: Direito do Consumidor
    content: |-
      Assessoria e consultoria sobre direito do consumidor, incluindo elaboração de estudos e pareceres.

      Condução e defesa em procedimentos administrativos.

      No campo litigioso, ajuizamento de ações, elaboração de defesas e recursos.
  - title: Direito de Família e Sucessório
    content: |-
      Condução de processos consensuais ou litigiosos de divórcio e extinção de união estável, mediação e orientação do casal sobre aspectos patrimoniais.

      Condução de processos consensuais ou litigiosos de pensão alimentícia, alimentos gravídicos, reconhecimento ou negatória de paternidade, ação de guarda de menor.

      Elaboração de testamentos, condução de inventários judiciais e extrajudiciais e orientação de herdeiros sobre a partilha.

      Condução de processos judiciais de interdição
  - title: Direito Médico e da Saúde
    content: |-
      * **Médicos e Profissionais da Saúde**

      Consultoria preventiva na elaboração e revisão de contratos, termos de consentimento, termos de recusa de tratamento, etc.

      Orientações ético-legais relativas ao exercício da profissão.

      Atuação em Sindicância e Processo Ético Profissional perante os Conselhos Regionais e Federal.

      Atuação Judicial em casos envolvendo responsabilidade civil.

      Mediação e Conciliação na relação médico-paciente.
  - title: Service title
    content: Aliquam pulvinar, orci ac scelerisque tempus, felis leo sagittis justo,
      sit amet condimentum lorem nibh vel quam. Duis consectetur lorem ipsum, non
      efficitur urna viverra et.
- type: testimonialsblock
  template: testimonialsblock
  title: Testimonials
  section_id: testimonials
  component: testimonials_block.html
  subtitle: An optional subtitle of the section
  testimonialslist:
  - author: John Doe
    avatar: images/john_doe.jpg
    content: Vestibulum a nunc ut eros condimentum posuere. Nullam dapibus quis nunc
      non interdum. Pellentesque tortor ligula, gravida ac commodo eu.
  - author: Jane Roe
    avatar: images/jane_roe.jpg
    content: Sed laoreet magna commodo libero euismod sodales. Nunc ac libero convallis,
      interdum ligula vel, pretium diam. Integer commodo sem at dui sollicitudin,
      vel posuere justo laoreet.
- type: postsblock
  template: postsblock
  title: Latest from the Blog
  section_id: latest-posts
  component: posts_block.html
  subtitle: An optional subtitle of the section
  num_posts_displayed: 2
  actions:
  - label: View Blog
    url: blog/index.html
- type: contactblock
  template: contactblock
  title: Contact Us
  section_id: contact
  component: contact_block.html
  subtitle: An optional subtitle of the section
layout: home
menu:
  main:
    weight: 1

---
