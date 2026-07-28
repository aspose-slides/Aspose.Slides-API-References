---
title: GetPresentationText()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Pobiera surowy tekst ze slajdów
type: docs
weight: 40
url: /pl/aspose.slides/ipresentationfactory/getpresentationtext/
---
## IPresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) metoda


Pobiera surowy tekst ze slajdów

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Plik wejściowy |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Tryb ekstrakcji |

### Wartość zwracana

Instancja [PresentationText](../../presentationtext/) zawierająca tablicę SlideText reprezentującą surowy tekst slajdów

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) metoda


Pobiera surowy tekst ze slajdów

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień wejściowy |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Tryb ekstrakcji |

### Wartość zwracana

Instancja [PresentationText](../../presentationtext/) zawierająca tablicę SlideText reprezentującą surowy tekst slajdów

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) metoda


Pobiera surowy tekst ze slajdów

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień wejściowy |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Tryb ekstrakcji |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opcje ładowania |

### Wartość zwracana

Instancja [PresentationText](../../presentationtext/) zawierająca tablicę SlideText reprezentującą surowy tekst slajdów

## Zobacz także

* Wyliczenie [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IPresentationText](../../ipresentationtext/)
* Klasa [String](../../../system/string/)
* Klasa [IPresentationFactory](../)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [ILoadOptions](../../iloadoptions/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)