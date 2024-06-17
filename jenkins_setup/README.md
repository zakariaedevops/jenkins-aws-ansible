Nom de rôle
=========

Une brève description du rôle se trouve ici.

Exigences
------------

Tous les prérequis qui peuvent ne pas être couverts par Ansible lui-même ou par le rôle doivent être mentionnés ici. Par exemple, si le rôle utilise le module EC2, il peut être judicieux de mentionner dans cette section que le package boto est requis.

Variables de rôle
---------------

Une description des variables réglables pour ce rôle doit être placée ici, y compris toutes les variables qui se trouvent dans defaults/main.yml, vars/main.yml et toutes les variables qui peuvent/devraient être définies via les paramètres du rôle. Toutes les variables lues à partir d'autres rôles et/ou de la portée globale (c'est-à-dire les variables d'hôte, les variables de groupe, etc.) doivent également être mentionnées ici.

Dépendances
------------

Une liste des autres rôles hébergés sur Galaxy doit se trouver ici, ainsi que tous les détails concernant les paramètres qui peuvent devoir être définis pour d'autres rôles, ou les variables utilisées à partir d'autres rôles.

Exemple de manuel de jeu
----------------

Inclure un exemple de la façon d'utiliser votre rôle (par exemple, avec des variables transmises en tant que paramètres) est également toujours intéressant pour les utilisateurs :

     - hôtes : serveurs
       les rôles:
          - { rôle : nom d'utilisateur.nom de rôle, x : 42 }

Licence
-------

BSD

Informations sur l'auteur
-------------------

Une section facultative permettant aux auteurs du rôle d'inclure des informations de contact ou un site Web (le HTML n'est pas autorisé).