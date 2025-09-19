---
layout: default
title: "Contact — Nina Neuhoff"
lang: fr
permalink: /contact/
---

<article class="page">
## CONTACT

Vous avez des questions ou souhaitez un devis gratuit et sans engagement ? Envoyez-moi simplement un message via le formulaire de contact – je vous répondrai dans les plus brefs délais.

Pour m’aider à traiter votre demande de traduction efficacement, merci de fournir autant que possible les informations suivantes :
- Type de texte et objectif (ex. site web, brochure, réseaux sociaux)  
- Public cible  
- Volume / longueur  
- Délai souhaité  
- Format ou contraintes de mise en page  
- Exigences particulières ou remarques

<form class="contact-form" action="https://formspree.io/f/mldwqbvj" method="POST" enctype="multipart/form-data">
  <label class="field">Nom <span class="required">*</span>
    <input type="text" name="name" required aria-required="true">
  </label>

  <label class="field">Adresse e-mail <span class="required">*</span>
    <input type="email" name="email" required aria-required="true">
  </label>

  <label class="field">Pièce jointe
    <input type="file" name="attachment">
  </label>

  <label class="field">Texte / Message <span class="required">*</span>
    <textarea name="message" required aria-required="true"></textarea>
  </label>

  <!-- nach Senden auf Danke-Seite weiterleiten -->
  <input type="hidden" name="_next" value="{{ site.url }}/merci/">

  <button type="submit">Envoyer</button>
</form>
</article>
