---
title: get_url method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---
## get_url(self, id, referrer) {#int-int}
Retourneert een URL naar een extern object.
            This method always called if **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** returned [`LinkEmbedDecision.LINK`](/slides/python-net/nl/aspose.slides.export/linkembeddecision/LINK) and may be called if **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** returned [`LinkEmbedDecision.EMBED`](/slides/python-net/nl/aspose.slides.export/linkembeddecision/EMBED) but embedding is impossible.
            Can be called multiple time for same object id.

### Retour

URL van extern object of None als dit object genegeerd moet worden.



```python
def get_url(self, id, referrer):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| id | **int** | Object-id. Deze id is operation-breed uniek. |
| referrer | **int** | id van het verwezende object of 0, als het object wordt verwezen door het basisedocument. Kan worden gebruikt om een relatieve link te genereren. |



### Zie ook
* klasse [`ILinkEmbedController`](/slides/python-net/nl/aspose.slides.export/ilinkembedcontroller)
* module [`aspose.slides.export`](/slides/python-net/nl/aspose.slides.export)
* bibliotheek [`Aspose.Slides`](/slides/python-net)