---
title: ExternalResourceResolver class
second_title: Aspose.Slides pour Python via l'API .NET
description: 
type: docs
url: /fr/aspose.slides.importing/externalresourceresolver/
---
## ExternalResourceResolver classe

classe Callback utilisée pour résoudre les ressources externes lors de l'importation de documents Html, Svg.  
L'utilisation de ce résolveur pourrait créer une vulnérabilité lorsqu'un fichier HTML ou SVG fourni par le client permet au logiciel serveur d'obtenir un fichier local ou réseau. Utilisez-le avec prudence. Il est recommandé de ne pas spécifier ExternalResourceResolver du tout (seuls les objets incorporés seront lus) ou de créer une sous-classe qui vérifie si l'uri spécifié est valide.

Le type ExternalResourceResolver expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/fr/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | Résout l'URI absolu à partir des URI de base et relatifs. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/fr/aspose.slides.importing/externalresourceresolver/get_entity/#str) | Mappe un URI vers un objet contenant la ressource réelle. |


### Voir aussi
* module [`aspose.slides.importing`](/slides/python-net/fr/aspose.slides.importing)
* bibliothèque [`Aspose.Slides`](/slides/python-net)