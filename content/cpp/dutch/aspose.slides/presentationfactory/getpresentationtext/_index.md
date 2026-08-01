---
title: GetPresentationText()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de ruwe tekst van de dia's op
type: docs
weight: 53
url: /nl/aspose.slides/presentationfactory/getpresentationtext/
---
## PresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) methode

Haalt de ruwe tekst van de dia's op

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Invoerbestand |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extractiemodus |

### Retourwaarde

De instantie van [PresentationText](../../presentationtext/) die de SlideText-array bevat die de ruwe dia-tekst weergeeft

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) methode

Haalt de ruwe tekst van de dia's op

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Invoerstroom |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extractiemodus |

### Retourwaarde

De instantie van [PresentationText](../../presentationtext/) die de SlideText-array bevat die de ruwe dia-tekst weergeeft

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) methode

Haalt de ruwe tekst van de dia's op

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Invoerstroom |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extractiemodus |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Laadopties |

### Retourwaarde

De instantie van [PresentationText](../../presentationtext/) die de SlideText-array bevat die de ruwe dia-tekst weergeeft

## Zie ook

* Enumeratie [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPresentationText](../../ipresentationtext/)
* Klasse [String](../../../system/string/)
* Klasse [PresentationFactory](../)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [ILoadOptions](../../iloadoptions/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)