---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Tworzy nową ramkę audio powiązaną z zewnętrznym plikiem audio i wstawia ją do kolekcji kształtów w określonym indeksie.
type: docs
weight: 274
url: /pl/aspose.slides/shapecollection/insertaudioframelinked/
---
## ShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) metoda

Tworzy nową ramkę audio powiązaną z zewnętrznym plikiem audio i wstawia ją do kolekcji kształtów w określonym indeksie.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, w którym ma zostać wstawiona ramka audio. |
| x | **float** | Współrzędna x nowej ramki audio, wyrażona w punktach. |
| y | **float** | Współrzędna y nowej ramki audio, wyrażona w punktach. |
| width | **float** | Szerokość nowej ramki audio, wyrażona w punktach. |
| height | **float** | Wysokość nowej ramki audio, wyrażona w punktach. |
| fname | [System::String](../../../system/string/) | Ścieżka lub nazwa zewnętrznego pliku audio do połączenia. |

### Wartość zwracana

Nowo utworzony [IAudioFrame](../../iaudioframe/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IAudioFrame](../../iaudioframe/)
* Klasa [String](../../../system/string/)
* Klasa [ShapeCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)