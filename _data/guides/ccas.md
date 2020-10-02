---
title: Dématérialiser l'instruction des dossiers dans un CCAS
tagline: Vous êtes un CCAS ou un éditeur de logiciel ? Nous vous accompagnons avec l'API Particulier pour accéder facilement aux données de la CAF et de la DGFIP.
tags: cas usage, api particulier, CCAS
image: dossier.jpg
api:
  - API Particulier
---

Les Centres Communaux d'Action Social sont amenés à instruire de nombreux dossiers d'obtention des aides sociales légales.

Ces dossiers utilisent généralement l'adresse, le quotient familial de la Caisse d’Allocations Familiales (CAF), la composition du foyer, l'avis d'imposition.

Avec la brique API Particulier vous avez la possibilité de diminuer les erreurs et les fraudes et faciliter le traitement des dossiers par vos équipes en accèdant **facilement aux données nécessaires** au calcul.

En intégrant la brique API Particulier dans votre système d'information, ou votre site internet :

- Vous accèdez facilement aux données de la CAF et de la DGFIP.
- Vous n'avez **plus besoin de demander** d'avis fiscal ou de quotient familial aux parents
- Vous n'avez **pas de vérifications supplémentaires** car les informations sont **certifiées**
- La démarche peut-être faite 100% en ligne

## Vous utilisez les données de la CAF ou de la DGFIP ?

Voici les données de la CAF (composition familiale du foyer du demandeur) et de la DGFIP (pour vérifier les conditions d'éligibilité d'une demande) accessibles directement avec notre API, ce sont les données les plus utilisées pour ce services, mais la liste ci-dessous n'est pas exhaustive :

| Donnée            | Commentaire                                                                                   |
| ----------------- | --------------------------------------------------------------------------------------------- |
| Allocataire       | L'état-civil du demandeur (nom prénom date de naissance)                                      |
| Enfant(s)         | Le/La/Les enfant(s) (nom, prenom, date de naissance)                                          |
| Quotient Familial | Le quotient familial calculé par la CAF                                                       |
| Avis d'imposition | statut d’imposition, montant de l'impôt, revenu fiscal de référence, nombre de parts fiscales |
| Adresse           | L'adresse du foyer et/ou l'adresse fiscale du demandeur                                       |

## Comment formuler une demande ?

L'utilisation des données par les CCAS est encadrée légalement. Vous pouvez motiver votre demande à l'aide des articles suivants :

- Article <External href="https://www.legifrance.gouv.fr/affichCodeArticle.do?idArticle=LEGIARTI000026799356&cidTexte=LEGITEXT000006074069&dateTexte=20121219">L.312-1</External> et <External href="https://www.legifrance.gouv.fr/affichCodeArticle.do?idArticle=LEGIARTI000031106561&cidTexte=LEGITEXT000006074069&dateTexte=20150809"> R123-5 </External> du _Code de l'action sociale et des familles_

- Article <External href="https://www.legifrance.gouv.fr/affichCodeArticle.do?idArticle=LEGIARTI000033219997&cidTexte=LEGITEXT000031366350&dateTexte=20161009">L.114-8</External> et <External href="https://www.legifrance.gouv.fr/affichCodeArticle.do;jsessionid=83A5E43D6A6710F0F0FFE705AA476AA5.tplgfr26s_3?cidTexte=LEGITEXT000031366350&idArticle=LEGIARTI000038029900&dateTexte=20190213&categorieLien=id#LEGIARTI000038029900">R114-9-3 </External> du _Code des relations entre le public et l'administration_

Si vous travaillez avec un des éditeurs ou intégrateurs, <a href='#editeurs'>consultez la section éditeurs.</a>

<NextSteps/>
<br/>
<Button href="https://datapass.api.gouv.fr/api-particulier?scopes=%7B%22dgfip_avis_imposition%22%3Atrue%2C%22dgfip_adresse%22%3Atrue%2C%22cnaf_quotient_familial%22%3Atrue%2C%22cnaf_allocataires%22%3Atrue%2C%22cnaf_enfants%22%3Atrue%2C%22cnaf_adresse%22%3Afalse%7D">Remplir une demande</Button>

## Editeurs

Si vous travaillez avec l'un des éditeurs ou intégrateurs ci-dessous vous pouvez faire une demande simplifiée :

| Editeur | Nom de la solution       | Date           | Lien vers la demande                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ------- | ------------------------ | -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Up      | Millesime Action Sociale | Mi-Mai 2020    | <External href="https://datapass.api.gouv.fr/api-particulier?scopes=%7B%22dgfip_avis_imposition%22%3Atrue%2C%22dgfip_adresse%22%3Atrue%2C%22cnaf_quotient_familial%22%3Atrue%2C%22cnaf_allocataires%22%3Atrue%2C%22cnaf_enfants%22%3Atrue%2C%22cnaf_adresse%22%3Afalse%7D">Remplir une demande</External>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| Arpège  | Sonate Opus              | Septembre 2020 | <External href="https://datapass.api.gouv.fr/api-particulier?intitule=R%C3%A9cup%C3%A9ration%20du%20Quotient%20Familial%20et%20des%20Imp%C3%B4ts%20pour%20les%20aides%20sociales%20facultatives%20et%20les%20services%20%C3%A0%20la%20personne%20du%20CCAS&description=Le%20CCAS%20de%20notre%20commune%20module%20le%20montant%20des%20aides%20octroy%C3%A9es%20aux%20usagers%20en%20difficult%C3%A9%20en%20fonction%20du%20QF.%0ALe%20prix%20des%20services%20%C3%A0%20la%20personne%20pour%20les%20a%C3%AEn%C3%A9s%20et%20personnes%20en%20situation%20de%20handicap%20est%20calcul%C3%A9%20en%20fonction%20de%20l%E2%80%99imp%C3%B4t%20sur%20le%20revenu.%20%0ADans%20un%20esprit%20de%20simplification%20et%20de%20s%C3%A9curit%C3%A9%2C%20nous%20souhaitons%20ne%20pas%20demander%20aux%20familles%20les%20informations%20de%20calcul%20mais%20plut%C3%B4t%20nous%20baser%20sur%20les%20donn%C3%A9es%20propos%C3%A9es%20par%20API%20Particulier.%0ANous%20utilisons%20le%20logiciel%20Sonate%20%C3%A9dit%C3%A9%20par%20la%20Soci%C3%A9t%C3%A9%20Arp%C3%A8ge.&data_recipients=agents%20instructeurs%20des%20demandes%20d'aides%2C%20agents%20instructeurs%20des%20demandes%20d'inscriptions%20aux%20services%20%C3%A0%20la%20personne%2C%20...&data_retention_period=12&fondement_juridique_title=Pr%C3%A9ciser%20ici%20les%20d%C3%A9lib%C3%A9rations%20du%20conseil%20d'administration%20qui%20d%C3%A9taillent%20les%20modalit%C3%A9s%20de%20calcul%20du%20montant%20des%20aides%20et%2Fou%20du%20prix%20de%20services.%20%0ALorsque%20le%20calcul%20du%20montant%20des%20aides%20est%20%C3%A0%20la%20libre%20appr%C3%A9ciation%20du%20travailleur%20social%20ou%20de%20la%20commission%20d%E2%80%99attribution%2C%20pr%C3%A9ciser%20sur%20quels%20%C3%A9l%C3%A9ments%20se%20basent%20la%20d%C3%A9cision.&fondement_juridique_url=Joindre%20les%20d%C3%A9lib%C3%A9rations%20ou%20proc%C3%A9dures%20internes%20concern%C3%A9es.&scopes=%7B%22dgfip_avis_imposition%22%3Atrue%2C%22dgfip_adresse%22%3Afalse%2C%22cnaf_quotient_familial%22%3Atrue%2C%22cnaf_allocataires%22%3Afalse%2C%22cnaf_enfants%22%3Afalse%2C%22cnaf_adresse%22%3Afalse%7D">Remplir une demande</External> |

Vous êtes un éditeur et vous souhaitez apparaître dans cette liste ? Écrivez-nous à [contact@particulier.api.gouv.fr](mailto:contact@particulier.api.gouv.fr)