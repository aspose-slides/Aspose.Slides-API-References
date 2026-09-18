---
title: ILinkEmbedController class
second_title: Aspose.Slides for Python via .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController osztály

Visszahívási interfész, amely meghatározza, hogyan kell az objektumot feldolgozni mentés közben.

Az ILinkEmbedController típus a következő tagokat tartalmazza:

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension)`](/slides/python-net/hu/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/#int-bytes-str-str-str) | Meghatározza, hogy hol kell az objektumot tárolni.<br/>            Ez a módszer minden egyes objektumazonosítóhoz egyszer kerül meghívásra.<br/>            Nem garantált, hogy nem lesz két objektum azonos adat, semanticName és contentType értékekkel, de eltérő azonosítóval. |
| [`get_url(self, id, referrer)`](/slides/python-net/hu/aspose.slides.export/ilinkembedcontroller/get_url/#int-int) | Visszaad egy URL-t egy külső objektumhoz.<br/>            Ez a módszer mindig akkor hívódik, ha **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** [`LinkEmbedDecision.LINK`](/slides/python-net/hu/aspose.slides.export/linkembeddecision/LINK) értéket ad vissza, és előfordulhat, ha **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** [`LinkEmbedDecision.EMBED`](/slides/python-net/hu/aspose.slides.export/linkembeddecision/EMBED) értéket ad vissza, de a beágyazás lehetetlen.<br/>            Többször is hívható ugyanazon objektumazonosító esetén. |
| [`save_external(self, id, entity_data)`](/slides/python-net/hu/aspose.slides.export/ilinkembedcontroller/save_external/#int-bytes) | Ment egy külső objektumot. |

### Lásd még
* modul [`aspose.slides.export`](/slides/python-net/hu/aspose.slides.export)
* könyvtár [`Aspose.Slides`](/slides/python-net)