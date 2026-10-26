---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides dla C++ – odwołanie API
description: Tworzy nową ramkę audio powiązaną z zewnętrznym plikiem audio i wstawia ją do kolekcji kształtów w określonym indeksie.
type: docs
weight: 235
url: /pl/aspose.slides/ishapecollection/insertaudioframelinked/
---
## IShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) metoda

Tworzy nową ramkę audio powiązaną z zewnętrznym plikiem audio i wstawia ją do kolekcji kształtów w określonym indeksie.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, w którym ma zostać wstawiona ramka audio. |
| x | **float** | Współrzędna x nowej ramki audio, w punktach. |
| y | **float** | Współrzędna y nowej ramki audio, w punktach. |
| width | **float** | Szerokość nowej ramki audio, w punktach. |
| height | **float** | Wysokość nowej ramki audio, w punktach. |
| fname | [System::String](../../../system/string/) | Ścieżka lub nazwa zewnętrznego pliku audio do powiązania. |

### Wartość zwracana

Nowo utworzony [IAudioFrame](../../iaudioframe/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IAudioFrame](../../iaudioframe/)
* Klasa [String](../../../system/string/)
* Klasa [IShapeCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)