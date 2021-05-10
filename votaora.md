---
layout: page
title: Elezioni 2021

#background_image: url('assets/img/backgrounds/in_costruzione.png')

sections:

#  - type: call-to-action.html
#    section_id: votaora_old
#    background_style: bg-primary
#    title: Qui sotto trovi la guida video per il voto # <br/>  <br/> Puoi votare martedì 11 dalle 9 alle 19 e mercoledì 12 maggio dalle 9 alle 18 su Eligo
#    actions:
#      - title: Vai ai programmi
#        url: 'elezioni2021#programmi'
#        class: btn-success
#      - title: Guida dettagliata (PDF)
#        url: 'https://www.unifi.it/upload/sub/elezioni/studenti_2021_2023/guida_voto_eligo.pdf'
#        class: btn-warning
#      - title: VOTA ORA!
#        url: 'https://unifi.evoting.it/login.aspx?id=1iGS16gjbPE%253d'
#        class: btn-success

  - type: members2.html
    section_id: votaora
    title: Puoi votare martedì 11 dalle 9 alle 19 e mercoledì 12 maggio dalle 9 alle 18 su Eligo
    background_style: bg-primary text-white
    members:
      - title: qui sotto trovi anche video-guida rapida al voto
        text:
        image: /elezioni2021/asset/votaora2.png
        url: 'https://unifi.evoting.it/login.aspx?id=1iGS16gjbPE%253d'

---

<html>
    <style>
      .wrap-element {
        position: relative;
        overflow: hidden;
        padding-top: 56.25%;
      }
      .wrapped-iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        border: 0;
      }
    </style>
  <body>
    <div class="wrap-element">
      <iframe class="wrapped-iframe" src="https://www.youtube.com/embed/S-sodvEjJ5k" gesture="media" allow="encrypted-media" allowfullscreen></iframe>
    </div>
  </body>
</html>
