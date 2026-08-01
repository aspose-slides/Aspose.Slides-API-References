---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw audioframe gekoppeld aan een extern audiobestand en voegt het in de vormverzameling in op de opgegeven index.
type: docs
weight: 274
url: /nl/aspose.slides/shapecollection/insertaudioframelinked/
---
## ShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) methode


Maakt een nieuw audioframe gekoppeld aan een extern audiobestand en voegt het in de vormverzameling in op de opgegeven index.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De index beginnend bij nul waarop het audioframe moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe audioframe, in punten. |
| y | **float** | De y-coördinaat van het nieuwe audioframe, in punten. |
| width | **float** | De breedte van het nieuwe audioframe, in punten. |
| height | **float** | De hoogte van het nieuwe audioframe, in punten. |
| fname | [System::String](../../../system/string/) | Het pad of de naam van het externe audiobestand om te koppelen. |

### Retourwaarde

Het nieuw aangemaakte [IAudioFrame](../../iaudioframe/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [String](../../../system/string/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)