---
title: get_url method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---
## get_url(self, id, referrer) {#int-int}
Returnerar en URL till ett externt objekt.
            Denna metod anropas alltid om **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** returned [`LinkEmbedDecision.LINK`](/slides/python-net/sv/aspose.slides.export/linkembeddecision/LINK) och kan anropas om **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** returned [`LinkEmbedDecision.EMBED`](/slides/python-net/sv/aspose.slides.export/linkembeddecision/EMBED) men inbäddning är omöjlig.
            Kan anropas flera gånger för samma objekt-id.

### Returnerar

URL för externt objekt eller None om detta objekt ska ignoreras.



```python
def get_url(self, id, referrer):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| id | **int** | Objekt-id. Detta id är unikt för hela operationen. |
| referrer | **int** | Id för refererande objekt eller 0, om objektet refereras av rot-dokumentet. Kan användas för att generera relativ länk. |



### Se även
* klass [`ILinkEmbedController`](/slides/python-net/sv/aspose.slides.export/ilinkembedcontroller)
* modul [`aspose.slides.export`](/slides/python-net/sv/aspose.slides.export)
* bibliotek [`Aspose.Slides`](/slides/python-net)