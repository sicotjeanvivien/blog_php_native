# BLOG EN PHP NATIVE

Le but de l'exercice est de mettre en place une structure d'application respectant le disgnPattern MVC via un blog. Nous allons mettre en place :
    - un router permattant de gérer les pages via les URL
    - une authentification permettant aux utilisateur de se connecter
    - CRUD d'article permattant de gérer les données
    - une gestion de formulaire 
  
## ETAPE 1 : ROUTER

Nous allons commencer notre projet par la mise en place du router. Le router permet d'éxecuter le contrôleur lié à une URL, pour renvoyer la vue/template demandé par le client.

### Indications : 
  
Le projet se compose de 4 répertoires principaux :
  - lib => correspond aux fonctionnalités de notre application
  - public => correspond à la porte d'entrée de notre application; le nom de domaine cible directement ce répertoire; cela permet de limité l'accés des utiloisateurs aux fichiers de l'application
  - src => partie logique de notre application; utilise les fonctionnalités stockées dans le lib;
  - template => correspond aux vue/template de notre application
Le router est déjà mis en place.
Pour lancer le server, il faut se mettre via le terminal dans le répertoire racine de projet le utiliser la commande "php -S localhost:8000 -t public/".
La page home est accessible via l'url "http://localhost:8000/"
Attention pour accéder aux différentes page, il faut utilisé "http://localhost:8000/?page=nom_page"

### Consignes

Mise en place d'une nouvelle page. Sur le même modèle que la page "home" créer une nouvelle page nommée "contact". Il faudra penser :
  - à ajouter la route dans la constante ROUTING
  - créer un nouveau controller "ContactController"
  - créer le template dans template/contact/contact_base.phtml

## ETAPE 2 : AJOUT NAVBAR



