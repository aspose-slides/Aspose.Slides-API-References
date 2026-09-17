---
title: HtmlExternalResolver class
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides.importing/htmlexternalresolver/
---
## HtmlExternalResolver classe

Objet de rappel utilisé par la routine d'importation HTML pour obtenir les objets référencés tels que les images.
L'utilisation de ce résolveur pourrait créer une vulnérabilité lorsque le fichier HTML fourni par le client amènerait le logiciel serveur à récupérer un fichier local ou réseau. Utilisez-le avec prudence. Il est recommandé de ne pas spécifier HtmlExternalResolver du tout (seuls les objets incorporés seront lus) ou de créer une sous-classe qui vérifie si l'uri spécifiée est valide.

Le type HtmlExternalResolver expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides.importing/htmlexternalresolver/__init__/#) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/fr/aspose.slides.importing/htmlexternalresolver/resolve_uri/#str-str) | Résout l'URI absolue à partir de l'URI de base et de l'URI relative. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/fr/aspose.slides.importing/htmlexternalresolver/get_entity/#str) | Mappe une URI vers un objet contenant la ressource réelle. |

### Voir aussi
* module [`aspose.slides.importing`](/slides/python-net/fr/aspose.slides.importing)
* bibliothèque [`Aspose.Slides`](/slides/python-net)