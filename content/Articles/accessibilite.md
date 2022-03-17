---
title: "Fiche sur l'accessibilité"
date: 2022-03-17T18:12:40+01:00
author: Pierre La Rocca
draft: false
description: Fiche synthèse du site design-accessible.fr
---

## À quoi sert l'accessibilité numérique ?

L'accessibilité garantie qu'une chose peut être utilisée par le plus grand nombre de personnes possible. Appliquée au numérique, elle permet aux gens en situation de handicap de pouvoir accéder à l'information sans être discriminées sur des critères de capacités ou de besoins.

D'après le site [Design Accessible](https://design-accessible.fr/), en France :

- On estime qu’une personne sur 5 est en situation de handicap.
- 80 % de ces handicaps sont invisibles.
- 85% des personnes handicapées le deviennent au cours de leur vie.

Parmi les principales catégories de déficience, on trouve :

- Les troubles auditifs
- Les troubles moteurs
- Les troubles visuels
- Les troubles cognitifs

Ces déficiences modifient la manière d'user des services numériques. Elles sont multiformes et peuvent se conjuguer entre elles.
Elles se caractérisent par leur nature, leur degré de gravité et leur degré d'apparition (temporaire, permanent ou situationnel).

## Designer l'expérience d'accessibilité

L'objectif de la navigation étant de **trouver du contenu**, il est nécessaire de concevoir les pages web en se concentrant sur cette action.
On dit qu'un site est accessible s'il est **compatible avec l'ensemble des manières de saisir du texte ou de déclencher des actions**. Cela passe notamment par la prise en compte des nombreuses stratégies d'adaptation et d'outils d'assistance existants.

Le site liste **6 catégories principales sur lesquels concevoir l'accessibilité**.

![Schéma des six catégories d'accessibilité.](/images/cat-accessibilite.png)

## Todo list d'un site accessible

{{< rawhtml >}}
  <ul>
    <li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox"> Le contenu de la page doit &#xEA;tre <strong>lisible rapidement et facilement</strong>.</li>
    <li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox"> Les liens de navigation doivent <strong>explicites, m&#xEA;me hors contexte</strong>.</li>
    <li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox"> Le parcours doit &#xEA;tre coh&#xE9;rent et sa structure doit <strong>respecter une hi&#xE9;rarchie pertinente</strong>.</li>
  </ul>
  <h3 class="mume-header" id="couleurs">Couleurs &#x1F3A8;</h3>

  <ul>
    <li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox"> Les textes et &#xE9;l&#xE9;ments d&apos;interface doivent &#xEA;tre <strong>contrast&#xE9;s</strong>.</li>
    <li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox"> Les informations <strong>ne doivent pas &#xEA;tre uniquement v&#xE9;hicul&#xE9;s par la couleur</strong>.</li>
  </ul>
  <h3 class="mume-header" id="formulaires-%EF%B8%8F">Formulaires &#x2611;&#xFE0F;</h3>

  <ul>
    <li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox"> Les champs doivent &#xEA;tre nomm&#xE9;s clairement et leur obligation de remplissage doit &#xEA;tre explicite.</li>
    <li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox"> Le formulaire ne doit pas g&#xE9;n&#xE9;rer d&apos;&#xE9;v&#xE8;nements surprenants et doit permettre la <strong>v&#xE9;rification des informations</strong>.</li>
    <li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox"> La correction d&apos;erreur doit guid&#xE9;e l&apos;utilisateur (type d&apos;erreur, lieu de l&apos;erreur, suggestion de correction...)</li>
  </ul>
  <h3 class="mume-header" id="conception-%EF%B8%8F">Conception &#x2699;&#xFE0F;</h3>

  <ul>
    <li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox"> Proposer de larges zones tactiles et des alternatives aux gestes complexes.</li>
    <li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox"> Eviter les distractions visuelles.</li>
  </ul>
  <h3 class="mume-header" id="navigation">Navigation &#x1F9ED;</h3>

  <ul>
    <li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox"> Site <em>responsive</em>.</li>
    <li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox"> Acc&#xE8;s simplifi&#xE9; aux contenus cach&#xE9;s.</li>
    <li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox"> Proposer plusieurs moyens de navigation.</li>
    <li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox"> Ne pas bloquer l&apos;orientation d&apos;affichage.</li>
  </ul>
  <h3 class="mume-header" id="livrables">Livrables &#x1F5A5;</h3>

  <ul>
    <li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox"> Donner un <strong>titre unique &#xE0; chaque page</strong>.</li>
    <li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox"> Fournir des <strong>alternatives textuelles aux images et m&#xE9;dias</strong>.</li>
    <li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox"> Designer les diff&#xE9;rents &#xE9;tats d&apos;un composant pour fournir un <em>feedback</em> aux interactions.</li>
    <li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox"> Proposer des <strong>raccourcis d&apos;acc&#xE8;s au contenu</strong>.</li>
  </ul>
{{< /rawhtml >}}

Prendre en compte l'ensemble de ces conseils permet de designer des services numériques accessibles au plus grand nombre.
