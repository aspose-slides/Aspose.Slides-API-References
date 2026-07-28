---
title: Add()
second_title: Aspose.Slides dla API C++
description: Dodaje zamknięte napisy WebVTT na koniec kolekcji.
type: docs
weight: 27
url: /pl/aspose.slides/captionscollection/add/
---
## CaptionsCollection::Add(System::String, System::String) metoda


Dodaje zamknięte napisy WebVTT na koniec kolekcji.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::String filePath) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Etykieta zamkniętych napisów. |
| filePath | [System::String](../../../system/string/) | Ścieżka do pliku WebVTT. |

### Wartość zwracana

Dodana instancja [ICaptions](../../icaptions/).

## CaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) metoda


Dodaje zamknięte napisy WebVTT na koniec kolekcji ze strumienia.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Etykieta zamkniętych napisów. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień wejściowy zawierający dane w formacie WebVTT. |

### Wartość zwracana

Dodana instancja [ICaptions](../../icaptions/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ICaptions](../../icaptions/)
* Klasa [String](../../../system/string/)
* Klasa [CaptionsCollection](../)
* Klasa [Stream](../../../system.io/stream/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)