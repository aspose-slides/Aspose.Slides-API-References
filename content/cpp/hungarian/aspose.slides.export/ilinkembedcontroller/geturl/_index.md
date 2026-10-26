---
title: GetUrl()
second_title: Aspose.Slides for C++ API referencia
description: "Visszaad egy URL-t egy külső objektumra. Ez a metódus mindig meghívásra kerül, ha ILinkEmbedController::GetObjectStoringLocation visszaadta a LinkEmbedDecision::Link értéket, és meghívható, ha ILinkEmbedController::GetObjectStoringLocation visszaadta a LinkEmbedDecision::Embed értéket, de a beágyazás lehetetlen. Többször is meghívható ugyanazzal az objektumazonosítóval."
type: docs
weight: 14
url: /hu/aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController::GetUrl(int32_t, int32_t) metódus

Visszaad egy Url-t egy külső objektumra. Ez a metódus mindig meghívásra kerül, ha [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) [LinkEmbedDecision::Link](../../linkembeddecision/)-t adott vissza, és meghívható, ha [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) [LinkEmbedDecision::Embed](../../linkembeddecision/)-t adott vissza, de a beágyazás lehetetlen. Többször is meghívható ugyanazzal az objektumazonosítóval.

```cpp
virtual System::String Aspose::Slides::Export::ILinkEmbedController::GetUrl(int32_t id, int32_t referrer)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | **int32_t** | Objektum azonosító. Ez az azonosító muvelet-szintűen egyedi. |
| referrer | **int32_t** | Az hivatkozó objektum azonosítója vagy 0, ha az objektumot a gyökérdokumentum hivatkozza. Használható relatív hivatkozás generálására. |

### Visszatérési érték

Külső objektum Url-je, vagy null, ha ezt az objektumot figyelmen kívül kell hagyni.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [ILinkEmbedController](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)