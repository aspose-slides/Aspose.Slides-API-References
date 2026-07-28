---
title: GetPresentationText()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Pobiera nieprzetworzony tekst ze slajdów
type: docs
weight: 53
url: /pl/aspose.slides/presentationfactory/getpresentationtext/
---
## PresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) metoda

Pobiera nieprzetworzony tekst ze slajdów

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Plik wejściowy |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Tryb ekstrakcji |

### Wartość zwracana

Instancja [PresentationText](../../presentationtext/) zawierająca tablicę SlideText reprezentującą nieprzetworzony tekst slajdów

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) metoda

Pobiera nieprzetworzony tekst ze slajdów

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień wejściowy |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Tryb ekstrakcji |

### Wartość zwracana

Instancja [PresentationText](../../presentationtext/) zawierająca tablicę SlideText reprezentującą nieprzetworzony tekst slajdów

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) metoda

Pobiera nieprzetworzony tekst ze slajdów

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień wejściowy |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Tryb ekstrakcji |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opcje ładowania |

### Wartość zwracana

Instancja [PresentationText](../../presentationtext/) zawierająca tablicę SlideText reprezentującą nieprzetworzony tekst slajdów

## Zobacz także

* Wyliczenie [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IPresentationText](../../ipresentationtext/)
* Klasa [String](../../../system/string/)
* Klasa [PresentationFactory](../)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [ILoadOptions](../../iloadoptions/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)