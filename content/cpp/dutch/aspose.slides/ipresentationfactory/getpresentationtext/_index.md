---
title: GetPresentationText()
second_title: Aspose.Slides voor C++ API Referentie
description: Haalt de ruwe tekst van de dia's op
type: docs
weight: 40
url: /nl/aspose.slides/ipresentationfactory/getpresentationtext/
---
## IPresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) method


Haalt de ruwe tekst van de dia's op

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Invoerbestand |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extractiemodus |

### Retourwaarde

De instantie van [PresentationText](../../presentationtext/) die de SlideText-array bevat die de ruwe dia-tekst weergeeft

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) method


Haalt de ruwe tekst van de dia's op

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Invoerstroom |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extractiemodus |

### Retourwaarde

De instantie van [PresentationText](../../presentationtext/) die de SlideText-array bevat die de ruwe dia-tekst weergeeft

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) method


Haalt de ruwe tekst van de dia's op

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options)=0
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

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationText](../../ipresentationtext/)
* Class [String](../../../system/string/)
* Class [IPresentationFactory](../)
* Class [Stream](../../../system.io/stream/)
* Class [ILoadOptions](../../iloadoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)