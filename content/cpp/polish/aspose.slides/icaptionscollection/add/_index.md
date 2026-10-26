---
title: Add()
second_title: Aspose.Slides – dokumentacja API dla C++
description: Dodaje napisy zamknięte WebVTT na koniec kolekcji.
type: docs
weight: 27
url: /pl/aspose.slides/icaptionscollection/add/
---
## ICaptionsCollection::Add(System::String, System::String) metoda


Dodaje napisy zamknięte WebVTT na koniec kolekcji.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::String filePath)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Etykieta napisów zamkniętych. |
| filePath | [System::String](../../../system/string/) | Ścieżka do pliku WebVTT. |

### Wartość zwracana

Instancja [ICaptions](../../icaptions/) została dodana.

## ICaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) metoda


Dodaje napisy zamknięte WebVTT na koniec kolekcji ze strumienia.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Etykieta napisów zamkniętych. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień wejściowy zawierający dane w formacie WebVTT. |

### Wartość zwracana

Instancja [ICaptions](../../icaptions/) została dodana.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [ICaptions](../../icaptions/)
* Klasa [String](../../../system/string/)
* Klasa [ICaptionsCollection](../)
* Klasa [Stream](../../../system.io/stream/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)