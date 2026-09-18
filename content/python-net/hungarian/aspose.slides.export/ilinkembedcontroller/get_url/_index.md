---
title: get_url method
second_title: Aspose.Slides Python számára .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---
## get_url(self, id, referrer) {#int-int}
Egy URL-t ad vissza egy külső objektumhoz.
Ez a metódus mindig meghívásra kerül, ha **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** [`LinkEmbedDecision.LINK`](/slides/python-net/hu/aspose.slides.export/linkembeddecision/LINK) értéket ad vissza, és meghívható, ha **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** [`LinkEmbedDecision.EMBED`](/slides/python-net/hu/aspose.slides.export/linkembeddecision/EMBED) értéket ad vissza, de a beágyazás lehetetlen.
Többször is meghívható ugyanazon objektum azonosítóval.

### Visszatérési érték

Az URL a külső objektumhoz, vagy None, ha ezt az objektumot figyelmen kívül kell hagyni.



```python
def get_url(self, id, referrer):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| id | **int** | Objektum azonosító. Ez az azonosító a mentés során műveletszinten egyedi. |
| referrer | **int** | Az hivatkozó objektum azonosítója vagy 0, ha az objektumot a gyökér dokumentum hivatkozza. Használható relatív link előállításához. |



### Lásd még
* osztály [`ILinkEmbedController`](/slides/python-net/hu/aspose.slides.export/ilinkembedcontroller)
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)