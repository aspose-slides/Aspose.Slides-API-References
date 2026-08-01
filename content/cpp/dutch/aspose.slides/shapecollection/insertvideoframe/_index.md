---
title: InsertVideoFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw videokader aan en voegt het in de shape-collectie in op de opgegeven index.
type: docs
weight: 222
url: /nl/aspose.slides/shapecollection/insertvideoframe/
---
## ShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) methode

Maakt een nieuw videokader aan en voegt het in de shape-collectie in op de opgegeven index.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop het videokader moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe videokader, in points. |
| y | **float** | De y-coördinaat van het nieuwe videokader, in points. |
| width | **float** | De breedte van het nieuwe videokader, in points. |
| height | **float** | De hoogte van het nieuwe videokader, in points. |
| fname | [System::String](../../../system/string/) | Het pad of de naam van het videobestand om in te sluiten. |

### Retourwaarde

Het nieuw aangemaakte [IVideoFrame](../../ivideoframe/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IVideoFrame](../../ivideoframe/)
* Class [String](../../../system/string/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)