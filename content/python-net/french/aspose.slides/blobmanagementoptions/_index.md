---
title: BlobManagementOptions class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions classe

Représente les options pouvant être utilisées pour gérer les règles de traitement des BLOB et d’autres paramètres des BLOB.

Le type BlobManagementOptions expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides/blobmanagementoptions/__init__/#) | Crée de nouvelles options de gestion des BLOB par défaut. |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/fr/aspose.slides/blobmanagementoptions/presentation_locking_behavior/) | Cette propriété indique si une instance de la classe Presentation peut être propriétaire de la source – fichier <br/>            ou flux pendant la durée de vie de l'instance. Si l'instance est propriétaire, elle verrouille la source. Cela permet <br/>            d'améliorer la consommation mémoire et les performances lors de la manipulation des BLOB, mais la source (flux ou fichier) <br/>            ne peut pas être modifiée pendant la durée de vie de l'instance de Presentation. |
| [`is_temporary_files_allowed`](/slides/python-net/fr/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | Cette propriété indique si des fichiers temporaires peuvent être créés lors de la manipulation des BLOB, ce qui réduit considérablement <br/>            la consommation mémoire mais nécessite des autorisations de création de fichiers.<br/>            Tous les fichiers seront supprimés une fois le travail sur la présentation terminé. |
| [`temp_files_root_path`](/slides/python-net/fr/aspose.slides/blobmanagementoptions/temp_files_root_path/) | Le chemin racine où les fichiers temporaires seront créés. Le répertoire temporaire du système sera utilisé par défaut. <br/>            Le processus d'hébergement doit disposer des autorisations pour <br/>            créer des fichiers et des dossiers à cet emplacement. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/fr/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | Définit la taille totale maximale (en octets) que tous les BLOB peuvent occuper en mémoire. Par défaut, tous les BLOB<br/>            sont chargés en mémoire ; ce n'est qu'une fois cette limite atteinte que des mécanismes alternatifs (comme les fichiers temporaires)<br/>            sont utilisés. Conserver les BLOB en mémoire maximise les performances mais peut engendrer une utilisation élevée de la mémoire. Utilisez<br/>            cette propriété pour adapter le comportement à votre environnement ou à vos exigences. |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)