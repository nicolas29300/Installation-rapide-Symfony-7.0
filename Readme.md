# Installation Rapide Symfony 7.0

ce dossier est là pour créer rapidement un projet symfony avec les composant de base.


## création du fichier de configuration
```touch .env.local```


## ajouter la configuration de la BDD dans le .env.local

Modifier le nom de l'identifiant du mot de passe du nom de la base de donnée et vérifier la version de my sql (```mysql --version```)

```DATABASE_URL="mysql://MON_IDENTIFIANT:MON8MOT8DE8PASSE@127.0.0.1:3306/LE_NOM_DE_MA_BDD?serverVersion=10.3.39-MariaDB&charset=utf8mb4"```

## Installer les composants
``` composer install ```

si demandé completer avec ```composer recipes```


## créer la BDD

```bin/console doctrine:database:create```

## créer les migrations
