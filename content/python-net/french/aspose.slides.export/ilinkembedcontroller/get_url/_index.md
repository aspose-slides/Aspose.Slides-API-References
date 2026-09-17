---
title: get_url method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---
## get_url(self, id, referrer) {#int-int}
Renvoie une URL vers un objet externe.
            Cette méthode est toujours appelée si **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** a renvoyé [`LinkEmbedDecision.LINK`](/slides/python-net/fr/aspose.slides.export/linkembeddecision/LINK) et peut être appelée si **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** a renvoyé [`LinkEmbedDecision.EMBED`](/slides/python-net/fr/aspose.slides.export/linkembeddecision/EMBED) mais l'incorporation est impossible.
            Peut être appelée plusieurs fois pour le même identifiant d'objet.

### Returns

URL de l'objet externe ou None si cet objet doit être ignoré.



```python
def get_url(self, id, referrer):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| id | **int** | Identifiant de l'objet. Cet identifiant est unique pour l'opération de sauvegarde. |
| referrer | **int** | identifiant de l'objet référent ou 0, si l'objet est référencé par le document racine. Peut être utilisé pour générer un lien relatif. |



### Voir aussi
* classe [`ILinkEmbedController`](/slides/python-net/fr/aspose.slides.export/ilinkembedcontroller)
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)