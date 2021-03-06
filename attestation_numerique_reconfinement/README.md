## Templates des scénarios

Les templates scénarios sont disponibles ici :

- [Génération Attestation numérique Reconfinement](./templates/generation_attestation.json)

- [Lancement Attestation Reconfinement](./templates/lancement_attestation.json)

## Description des scénarios

- Le scénario "Génération Attestation numérique Reconfinement" permet d'envoyer un message par Discord (avec la possibilité de remplacer par Telegram, Mail, etc..)
  
  Il attend en paramètres :
  - les coordonnées de l'utilisateur : nom, prenom, dateNaissance, lieuNaissance, adresse, codePostal, ville
  - et le motif de l'attestation : motifAttestation (valeurs possibles : travail, achats, sante, famille, handicap, sport_animaux, convocation, missions, enfants)

- Le scénario "Lancement Attestation Reconfinement" appelle le scénario précédent "Génération Attestation numérique Reconfinement"
  
  Il suffit de passer les paramètres attendus.

### Captures des scénarios

Génération Attestation numérique Reconfinement

![Onglet Général](./doc/images/generation_attestation_numerique_reconfinement.png)

Lancement attestation Reconfinement

![Onglet Scénario](./doc/images/lancement_attestation_reconfinement.png)

Message généré sur Discord

![Message Discord](./doc/images/message_discord.png)

Attestation numérique générée

![Attestation numérique](./doc/images/declaration_de_deplacement_attestation.png)
