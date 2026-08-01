---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw audioframe aan dat gekoppeld is aan een extern audiobestand en voegt het in de vormverzameling in op de opgegeven index.
type: docs
weight: 235
url: /nl/aspose.slides/ishapecollection/insertaudioframelinked/
---
## IShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) methode

Maakt een nieuw audioframe aan dat gekoppeld is aan een extern audiobestand en voegt het in de vormverzameling in op de opgegeven index.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop het audioframe moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe audioframe, in punten. |
| y | **float** | De y-coördinaat van het nieuwe audioframe, in punten. |
| width | **float** | De breedte van het nieuwe audioframe, in punten. |
| height | **float** | De hoogte van het nieuwe audioframe, in punten. |
| fname | [System::String](../../../system/string/) | Het pad of de naam van het externe audiobestand om mee te linken. |

### Retourwaarde

Het nieuw aangemaakte [IAudioFrame](../../iaudioframe/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAudioFrame](../../iaudioframe/)
* Klasse [String](../../../system/string/)
* Klasse [IShapeCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)