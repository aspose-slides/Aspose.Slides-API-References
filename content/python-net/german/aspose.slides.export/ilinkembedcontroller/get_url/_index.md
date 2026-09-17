---
title: get_url method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---
## get_url(self, id, referrer) {#int-int}
Gibt eine URL zu einem externen Objekt zurück.
            Diese Methode wird immer aufgerufen, wenn **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** [`LinkEmbedDecision.LINK`](/slides/python-net/de/aspose.slides.export/linkembeddecision/LINK) zurückgab und kann aufgerufen werden, wenn **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** [`LinkEmbedDecision.EMBED`](/slides/python-net/de/aspose.slides.export/linkembeddecision/EMBED) zurückgab, aber das Einbetten ist unmöglich.
            Kann mehrmals für dieselbe Objekt-ID aufgerufen werden.

### Rückgabewert

URL des externen Objekts oder None, wenn dieses Objekt ignoriert werden soll.



```python
def get_url(self, id, referrer):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| id | **int** | Objekt-ID. Diese ID ist operationweit eindeutig. |
| referrer | **int** | ID des referenzierenden Objekts oder 0, wenn das Objekt vom Stamm-Dokument referenziert wird. Kann zur Erzeugung eines relativen Links verwendet werden. |



### Siehe auch
* Klasse [`ILinkEmbedController`](/slides/python-net/de/aspose.slides.export/ilinkembedcontroller)
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)