# Instructions
Vous devez faire un programme générique qui pourra répondre à la problématique ci-dessous.

Un programme de type console est suffisant pour ce genre de test.

Vous pouvez utiliser le langage de programmation de votre choix. Veuillez prendre note que Télé-Québec utilise, en ce moment, le langage C# sur les plateformes .Net et .Net Core.

L’objectif est de pouvoir discuter ensemble de votre approche et de la façon dont vous avez abordé le problème.

Si vous n’arrivez pas à compléter le test, vous pouvez quand même nous envoyer votre code avec des commentaires et des annotations (expliquez pourquoi vous n’avez pas complété le test, décrivez-nous quelle approche vous pensez serait la bonne, etc.).

# Problématique
## Contexte
Vous avez accès à un premier fichier JSON (series.json) qui simule une base de données. Ce fichier contient une liste de séries télévisuelles (et leurs épisodes) que Télé-Québec possède.

Un deuxième fichier JSON (grille-tv.json) représente la diffusion planifiée de ces épisodes à la télévision linéaire traditionnelle.

Finalement, vous trouverez en annexe les règles contractuelles qui accompagnent ces séries télévisuelles et qui déterminent les restrictions imposées à Télé-Québec par les producteurs de ces séries.

**Télé-Québec désire exploiter au MAXIMUM les épisodes qu’elle possède sur le Web.**

Vous devrez, via votre code, charger les données des deux (2) fichiers JSON et déterminer les plages de temps maximum (date et heure de publication, ainsi que date et heure de retrait) pendant lesquelles Télé-Québec peut exploiter chacun des épisodes sur le Web.

Bonus : Fournir un test unitaire avec la librairie de votre choix.

## Annexe
### Contrats
**Série : L’Indice Bégin**

Droits pour la diffusion Web :
+ Chaque épisode peut être exploité sur le Web pour une période maximum de quatorze (14) jours consécutifs, période qui débute immédiatement après la diffusion à la télévision.

**Série : On parle de Western**

Droits pour la diffusion Web :
+ Chaque épisode peut être exploité sur le Web pour une période maximum de soixante (60) jours consécutifs, période qui débute immédiatement après la diffusion à la télévision.
+ L’exploitation des épisodes n’est pas du tout permise sur le Web les fins de semaines (samedi et dimanche).

**Série : Belle et Diaz**

Droits pour la diffusion Web :
+ Chaque épisode peut être exploité sur le Web pour une période maximum de trente (30) jours consécutifs, période qui débute immédiatement après la diffusion à la télévision
