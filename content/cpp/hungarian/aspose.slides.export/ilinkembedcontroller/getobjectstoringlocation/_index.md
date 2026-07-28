---
title: GetObjectStoringLocation()
second_title: Aspose.Slides C++ API referenciája
description: Meghatározza, hol kell tárolni az objektumot. Ez a metódus minden objektumazonosítóhoz egyszer kerül meghívásra. Nem garantált, hogy nem lesz két objektum azonos adat, semanticName és contentType értékekkel, de különböző azonosítóval.
type: docs
weight: 1
url: /hu/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---
## ILinkEmbedController::GetObjectStoringLocation(int32_t, System::ArrayPtr\<uint8_t\>, System::String, System::String, System::String) metódus

Meghatározza, hol kell tárolni az objektumot. Ez a metódus minden objektumazonosítóhoz egyszer kerül meghívásra. Nem garantált, hogy nem lesz két objektum azonos adat, semanticName és contentType értékekkel, de különböző azonosítóval.

```cpp
virtual LinkEmbedDecision Aspose::Slides::Export::ILinkEmbedController::GetObjectStoringLocation(int32_t id, System::ArrayPtr<uint8_t> entityData, System::String semanticName, System::String contentType, System::String recomendedExtension)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | **int32_t** | Objektumazonosító. Ez az azonosító a teljes mentési művelet során egyedi. |
| entityData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Objektum bináris adatai. Ez a paraméter lehet null, ha az objektum bináris adatai még nem álltak elő. |
| semanticName | [System::String](../../../system/string/) | Rövid szöveg, amely leírja az objektum jelentését. A vezérlő ezt felhasználhatja a külső objektumnév részének, de a diszpécser feladata biztosítani, hogy a nevek egyediek legyenek, és csak megengedett karaktereket tartalmazzanak. |
| contentType | [System::String](../../../system/string/) | Az objektum MIME típusa. |
| recomendedExtension | [System::String](../../../system/string/) | A fájlnév kiterjesztése, amely erre a MIME típusra ajánlott. |

### Visszatérési érték

Decision

## Lásd még

* Enum [LinkEmbedDecision](../../linkembeddecision/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [String](../../../system/string/)
* Osztály [ILinkEmbedController](../)
* Névtér [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)