# AutoAddVSCodeSupport

Ce package Unity simplifie l'intégration de VSCode avec Unity en automatisant l'importation et l'installation du package Unity nécessaire pour cette intégration. Il est conçu pour fonctionner avec le package [com.unity.ide.visualstudio](https://github.com/needle-mirror/com.unity.ide.visualstudio) pour faciliter l'utilisation de VSCode comme éditeur de code pour vos projets Unity.

## Installation

Pour utiliser ce package dans votre projet Unity, suivez ces étapes :

1. Téléchargez le dernier `.unitypackage` d'AutoAddVSCodeSupport depuis la [section des releases](https://github.com/quercyAP/AutoAddVSCodeSupport/releases) de ce dépôt.
2. Ouvrez votre projet Unity.
3. Naviguez vers `Assets` > `Import Package` > `Custom Package...` et sélectionnez le fichier `.unitypackage` téléchargé.
4. Unity affichera une fenêtre pour sélectionner les assets à importer. Assurez-vous que tout est sélectionné et cliquez sur `Import`.

## Utilisation en Ligne de Commande

Pour créer un nouveau projet Unity et importer automatiquement ce package, utilisez la commande suivante :

```sh
/opt/Unity/LTS/Editor/Unity -createProject [projectPath] -importPackage [absolutePath]/AutoAddVSCodeSupport.unitypackage
```
Remplacez `[projectPath]` par le chemin où vous souhaitez créer votre nouveau projet Unity et `[absolutePath]` par le chemin absolu du fichier AutoAddVSCodeSupport.unitypackage sur votre machine.

## Fonctionnalités

- **Automatisation de l'Installation** : Importe et installe automatiquement le package com.unity.ide.visualstudio nécessaire pour l'intégration de VSCode.
- **Configuration Simplifiée : Facilite** la configuration de VSCode comme éditeur de code pour vos projets Unity, permettant une intégration rapide et sans effort.

## Liens Externes

- Pour plus d'informations sur l'utilisation des arguments de ligne de commande avec l'éditeur Unity, consultez la documentation officielle : [Arguments de Ligne de Commande Unity](https://docs.unity3d.com/Manual/EditorCommandLineArguments.html).
- Pour voir le code source et obtenir plus de détails sur le package `com.unity.ide.visualstudio` utilisé pour l'intégration de VSCode, visitez : [com.unity.ide.visualstudio sur GitHub](https://github.com/needle-mirror/com.unity.ide.visualstudio).
