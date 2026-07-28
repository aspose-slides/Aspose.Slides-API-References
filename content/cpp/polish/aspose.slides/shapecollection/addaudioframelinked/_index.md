---
title: AddAudioFrameLinked()
second_title: Aspose.Slides dla C++ API Reference
description: Tworzy nową ramkę audio powiązaną z zewnętrznym plikiem audio i dodaje ją na koniec kolekcji kształtów.
type: docs
weight: 261
url: /pl/aspose.slides/shapecollection/addaudioframelinked/
---
## ShapeCollection::AddAudioFrameLinked(float, float, float, float, System::String) metoda

Tworzy nową ramkę audio powiązaną z zewnętrznym plikiem audio i dodaje ją na koniec kolekcji kształtów.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameLinked(float x, float y, float width, float height, System::String fname) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna x nowej ramki audio, w punktach. |
| y | **float** | Współrzędna y nowej ramki audio, w punktach. |
| width | **float** | Szerokość nowej ramki audio, w punktach. |
| height | **float** | Wysokość nowej ramki audio, w punktach. |
| fname | [System::String](../../../system/string/) | Ścieżka lub nazwa zewnętrznego pliku audio, który ma być połączony. |

### Wartość zwracana

Nowo utworzony [IAudioFrame](../../iaudioframe/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IAudioFrame](../../iaudioframe/)
* Klasa [String](../../../system/string/)
* Klasa [ShapeCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)