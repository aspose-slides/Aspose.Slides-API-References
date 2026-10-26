---
title: GetPresentationText()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Načte surový text ze snímků
type: docs
weight: 53
url: /cs/aspose.slides/presentationfactory/getpresentationtext/
---
## PresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) metoda

Načte surový text ze snímků

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Vstupní soubor |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Režim extrakce |

### Návratová hodnota

Instance [PresentationText](../../presentationtext/) obsahující pole SlideText představující surový text snímků

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) metoda

Načte surový text ze snímků

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Vstupní stream |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Režim extrakce |

### Návratová hodnota

Instance [PresentationText](../../presentationtext/) obsahující pole SlideText představující surový text snímků

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) metoda

Načte surový text ze snímků

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Vstupní stream |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Režim extrakce |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Možnosti načtení |

### Návratová hodnota

Instance [PresentationText](../../presentationtext/) obsahující pole SlideText představující surový text snímků

## Viz také

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IPresentationText](../../ipresentationtext/)
* Třída [String](../../../system/string/)
* Třída [PresentationFactory](../)
* Třída [Stream](../../../system.io/stream/)
* Třída [ILoadOptions](../../iloadoptions/)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)