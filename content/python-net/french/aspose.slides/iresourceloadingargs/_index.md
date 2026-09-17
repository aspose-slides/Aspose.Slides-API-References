---
title: IResourceLoadingArgs class
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides/iresourceloadingargs/
---
## IResourceLoadingArgs classe

Interface pour les arguments de chargement de ressources externes.

Le type IResourceLoadingArgs expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`original_uri`](/slides/python-net/fr/aspose.slides/iresourceloadingargs/original_uri/) | URI d'origine de la ressource tel qu'indiqué dans la présentation importée. |
| [`uri`](/slides/python-net/fr/aspose.slides/iresourceloadingargs/uri/) | URI de la ressource qui est utilisée pour le téléchargement si **Aspose.Slides.IResourceLoadingCallback.ResourceLoading(Aspose.Slide** <br/>            renvoie [`ResourceLoadingAction.DEFAULT`](/slides/python-net/fr/aspose.slides/resourceloadingaction/DEFAULT). <br/>            Initialement, elle est définie sur l'URI d'origine de la ressource, mais peut être redéfinie à n'importe quelle valeur. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`set_data(self, data)`](/slides/python-net/fr/aspose.slides/iresourceloadingargs/set_data/#bytes) | Définit les données fournies par l'utilisateur de la ressource qui sont utilisées si **Aspose.Slides.IResourceLoadingCallback.ResourceLoading(Aspose.Slide** <br/>            renvoie [`ResourceLoadingAction.USER_PROVIDED`](/slides/python-net/fr/aspose.slides/resourceloadingaction/USER_PROVIDED). |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)