---
title: IBlobManagementOptions class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions classe

Un Binary Large Object (BLOB) est une donnée binaire stockée comme une entité unique - c’est-à-dire que le BLOB peut être un audio, une vidéo ou la présentation elle-même.  
Un certain nombre de techniques sont utilisées pour optimiser la consommation de mémoire lors de la manipulation des BLOBs - qui ont déjà été stockés dans la présentation ou peuvent être ajoutés ultérieurement par programmation.  
En utilisant [`IBlobManagementOptions`](/slides/python-net/fr/aspose.slides/iblobmanagementoptions) vous pouvez modifier différents aspects du comportement concernant la gestion des BLOBs pour la durée de vie de l’instance [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation).

Le type IBlobManagementOptions expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/fr/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | Cette propriété définit si une instance de la classe Presentation peut être propriétaire de la source - fichier <br/>            ou flux pendant la durée de vie de l'instance. Si l'instance est propriétaire, elle verrouille la source. Cela aide <br/>            à améliorer la consommation de mémoire et les performances lors de la manipulation des BLOBs, mais la source (flux ou fichier) <br/>            ne peut pas être modifiée pendant la durée de vie de l'instance Presentation. Voici un exemple : |
| [`is_temporary_files_allowed`](/slides/python-net/fr/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | Cette propriété définit si des fichiers temporaires peuvent être créés lors de la manipulation des BLOBs, ce qui diminue fortement <br/>            la consommation de mémoire mais nécessite des autorisations pour créer des fichiers.<br/>            Tous les fichiers seront supprimés une fois le travail avec la présentation terminé. |
| [`temp_files_root_path`](/slides/python-net/fr/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | Le chemin racine où les fichiers temporaires seront créés. Le répertoire temporaire du système sera utilisé par défaut. <br/>            Le processus d’hébergement doit disposer des autorisations pour <br/>            créer des fichiers et dossiers à cet emplacement. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/fr/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | Définit la taille totale maximale (en octets) que tous les BLOBs peuvent occuper en mémoire. Par défaut, tous les BLOBs<br/>            sont chargés en mémoire ; seulement lorsque cette limite est atteinte des mécanismes alternatifs (comme les fichiers temporaires)<br/>            sont employés. Conserver les BLOBs en mémoire maximise les performances mais peut entraîner une utilisation élevée de la mémoire. Utilisez<br/>            cette propriété pour adapter le comportement à votre environnement ou à vos exigences. |


### Voir aussi
* classe [`IBlobManagementOptions`](/slides/python-net/fr/aspose.slides/iblobmanagementoptions)
* classe [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)