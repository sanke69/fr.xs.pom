SP POM File
===========

My main POM file for all projects.

This README also contains useful information about maven project management and git actions.

Git commands
------------

Ajouter un fichier au projet  
``` git add <file> ```

Mettre en base toutes les modifications  
``` git commit -a ```  
``` git commit -a -m "Message" ```

Modifier le dernier commit pour intégrer des modifications oubliées  
``` git commit --amend ```

Maven targets
-------------

Nettoyage du projet  
``` mvn clean ```

Compilation du projet  
``` mvn compile ```

Création d'un paquet: JAR|WAR|ZIP|...  
``` mvn package ```

Installation d'un module sur l'hôte  
``` mvn install ```

Définition d'une variable  
``` mvn <action> -D<nom de la variable>=<valeur> ```

Utilisation d'un profile  
``` mvn <action> -P<nom du profile> ```

Utilisation d'un profile  
``` mvn <action> -P<nom du profile> ```

Génération d'une release (plugin release)  
``` mvn release:perform ```  
``` mvn release:perform -Darguments="-P<profile> -D<variable>=<value> -D..." ```
