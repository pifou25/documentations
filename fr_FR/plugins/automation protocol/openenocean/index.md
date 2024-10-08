# Plugin Open Enocean

Ce plugin est un plugin permettant une compatibilité Enocean

# Configuration

## Configuration du plugin

> **Tip**
>
> Afin d’utiliser le plugin, vous devez le télécharger, l’installer et l’activer comme tout plugin Jeedom.

> **Important**
>
> La chose la plus importante ici est de sélectionner votre Contrôlleur USB (vous pouvez choisir Auto cela fonctionnera pour la clé Enocean USB300). Pour tout autre modèle il est préférable de le choisir dans la liste :

-   USB300 : EnOcean\_GmbH EnOean\_USB\_300\_DB
-   USB310 : FTDI FT232R\_USB\_UART
-   Jeedom Smart : ttyS1

L’autre option disponible sur cette page est : **Supprimerautomatiquement les périphériques exclus**. Celle-ci permet de supprimer les équipements de Jeedom lorsqu’il sont exclus.

Vous pouvez aussi vérifier l’état des dépendances et les relancer. En cas de soucis avec le plugin toujours relancer les dépendances même si OK dans le doute.

## Compatibilité

Vous pouvez trouver [ici](https://compatibility.jeedom.com/index.php?v=d&p=home&plugin=openenocean) la liste des modules compatible avec le plugin

# Le plugin

Rendez vous dans le menu plugins/protocole pour retrouver le plugin.

Sur cette page vous pourrez voir les modules déjà inclus.

Sur la partie haute de cette page vous avez plusieurs boutons (visibles selon que vous êtes en mode expert ou non)

-   Bouton ajouter : Permet d’ajouter certains modules qui n’ont pas de notions d’appairage ou qui nécessitent un envoi de commandes depuis Jeedom
-   Bouton Inclusion : Ce bouton permet de mettre Jeedom en Inclusion (plusieurs modes, seul le premier est disponible pour le moment)
-   Bouton Exclusion : Ce bouton permet de mettre Jeedom en Exclusion
-   Bouton Configuation : Ce bouton permet d’ouvrir la fenêtre de configuration du plugin
-   Bouton Santé : Ce bouton permet d’avoir un aperçu Santé de tous vos modules

# Equipement

Lorsque que vous cliquez sur un de vos modules, vous arrivez sur la pagede configuration de celui-ci :

-   Donner un nom au module
-   L’activer/le rendre visible ou non
-   Choisir son objet parent
-   Lui attribuer une catégorie
-   Definir un delai de surveillance de communication pour certains modules
-   Mettre un commentaire

Sur la partie droite vous trouverez :

-   Le profil de l’équipement (généralement auto détecté si le module le permet)
-   Choisir un modèle si pour ce profil plusieurs modèles sont disponibles
-   Voir le visuel

# Equipement avec configuration

Pour certains modules il est possible d’avoir un bouton configurer, en cliquant dessus vous arriverez sur une page permettant de configurercelui-ci

> **Important**
>
> Ici il vous suffit de choisir toutes les options et de cliquer sur appliquer. (Attention : il tous les paramètres sont envoyés, donc validez bien l’ensemble)

# Liste de compatibilité

Vous trouverez [ici](https://compatibility.jeedom.com/index.php?v=d&p=home&search=&plugin=openenocean) une liste de compatibilité de modules avec leur procédure d’inclusion si elles sont spécifiques.
