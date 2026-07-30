---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vytvoří nový audio rámeček propojený s externím audio souborem a vloží jej do kolekce tvarů na zadaném indexu.
type: docs
weight: 274
url: /cs/aspose.slides/shapecollection/insertaudioframelinked/
---
## ShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) method

Vytvoří nový audio rámeček propojený s externím audio souborem a vloží jej do kolekce tvarů na zadaném indexu.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Nulový index, na kterém se má vložit audio rámeček. |
| x | **float** | x-souřadnice nového audio rámečku, v bodech. |
| y | **float** | y-souřadnice nového audio rámečku, v bodech. |
| width | **float** | Šířka nového audio rámečku, v bodech. |
| height | **float** | Výška nového audio rámečku, v bodech. |
| fname | [System::String](../../../system/string/) | Cesta nebo název externího audio souboru, který se má propojit. |

### Návratová hodnota

Nově vytvořený [IAudioFrame](../../iaudioframe/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [String](../../../system/string/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)