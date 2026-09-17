---
title: ILinkEmbedController class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController classe

Interface de rappel utilisée pour déterminer comment l'objet doit être traité lors de l'enregistrement.

Le type ILinkEmbedController expose les membres suivants :

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension)`](/slides/python-net/fr/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/#int-bytes-str-str-str) | Détermine où l'objet doit être stocké.<br/>            Cette méthode est appelée une fois pour chaque identifiant d'objet.<br/>            Il n'est pas garanti qu'il n'y aura pas deux objets avec les mêmes données, semanticName et contentType mais avec des identifiants différents. |
| [`get_url(self, id, referrer)`](/slides/python-net/fr/aspose.slides.export/ilinkembedcontroller/get_url/#int-int) | Renvoie une URL vers un objet externe.<br/>            Cette méthode est toujours appelée si **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** a renvoyé [`LinkEmbedDecision.LINK`](/slides/python-net/fr/aspose.slides.export/linkembeddecision/LINK) et peut être appelée si **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** a renvoyé [`LinkEmbedDecision.EMBED`](/slides/python-net/fr/aspose.slides.export/linkembeddecision/EMBED) mais l'intégration est impossible.<br/>            Peut être appelée plusieurs fois pour le même identifiant d'objet. |
| [`save_external(self, id, entity_data)`](/slides/python-net/fr/aspose.slides.export/ilinkembedcontroller/save_external/#int-bytes) | Enregistre l'objet externe. |

### Voir aussi
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)