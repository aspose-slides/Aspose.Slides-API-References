---
title: InsertVideoFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw videoframe en voegt het toe aan de vormverzameling op de opgegeven index.
type: docs
weight: 183
url: /nl/aspose.slides/ishapecollection/insertvideoframe/
---
## IShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) methode

Maakt een nieuw videoframe en voegt het toe aan de vormverzameling op de opgegeven index.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nul-gebaseerde index waarop het videoframe moet worden ingevoegd. |
| x | **float** | Het x-coördinaat van het nieuwe videoframe, in punten. |
| y | **float** | Het y-coördinaat van het nieuwe videoframe, in punten. |
| width | **float** | De breedte van het nieuwe videoframe, in punten. |
| height | **float** | De hoogte van het nieuwe videoframe, in punten. |
| fname | [System::String](../../../system/string/) | Het pad of de naam van het video-bestand dat moet worden ingesloten. |

### Retourwaarde

Het nieuw aangemaakte [IVideoFrame](../../ivideoframe/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IVideoFrame](../../ivideoframe/)
* Class [String](../../../system/string/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)