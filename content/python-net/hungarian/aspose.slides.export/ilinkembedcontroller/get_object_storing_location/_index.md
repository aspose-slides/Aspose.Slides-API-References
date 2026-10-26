---
title: get_object_storing_location method
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---
## get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension) {#int-bytes-str-str-str}
Meghatározza, hogy hol kell tárolni az objektumot.
            Ez a metódus minden egyes objektum-azonosítóhoz egyszer hívódik.
            Nem garantált, hogy nem lesz két objektum azonos adat, semanticName és contentType értékekkel, de eltérő azonosítóval.

### Returns
Döntés

```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| id | **int** | Objektum-azonosító. Ez az azonosító a mentési művelet során egyedi. |
| entity_data | **bytes** | Objektum bináris adatai. Ez a paraméter lehet None, ha az objektum bináris adatai még nem lettek előállítva. |
| semantic_name | **str** | Rövid szöveg, amely leírja az objektum jelentését. A vezérlő használhatja ezt a külső objektumnév részeként, de a diszpécser feladata, hogy biztosítsa a nevek egyediségét és csak engedélyezett karakterek használatát. |
| content_type | **str** | Az objektum MIME típusa. |
| recomended_extension | **str** | A fájlnév kiterjesztése, amely ajánlott ehhez a MIME típushoz. |

### See Also
* class [`ILinkEmbedController`](/slides/python-net/hu/aspose.slides.export/ilinkembedcontroller)
* enumeration [`LinkEmbedDecision`](/slides/python-net/hu/aspose.slides.export/linkembeddecision)
* module [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)