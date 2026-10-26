---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří nový audio rámec propojený s externím audio souborem a vloží jej do kolekce tvarů na zadaném indexu.
type: docs
weight: 235
url: /cs/aspose.slides/ishapecollection/insertaudioframelinked/
---
## IShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) metoda


Vytvoří nový audio rámec propojený s externím audio souborem a vloží jej do kolekce tvarů na určený index.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Nulově indexované místo, kam se má audio rámec vložit. |
| x | **float** | Souřadnice x nového audio rámce v bodech. |
| y | **float** | Souřadnice y nového audio rámce v bodech. |
| width | **float** | Šířka nového audio rámce v bodech. |
| height | **float** | Výška nového audio rámce v bodech. |
| fname | [System::String](../../../system/string/) | Cesta nebo název externího audio souboru, který se má propojit. |

### Návratová hodnota

Nově vytvořený [IAudioFrame](../../iaudioframe/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAudioFrame](../../iaudioframe/)
* Třída [String](../../../system/string/)
* Třída [IShapeCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)