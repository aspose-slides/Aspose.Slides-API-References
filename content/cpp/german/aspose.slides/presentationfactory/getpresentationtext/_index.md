---
title: GetPresentationText()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft den Rohtext aus den Folien ab
type: docs
weight: 53
url: /de/aspose.slides/presentationfactory/getpresentationtext/
---
## PresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) Methode


Ruft den Rohtext aus den Folien ab

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Eingabedatei |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraktionsmodus |

### Rückgabewert

Die Instanz von [PresentationText](../../presentationtext/) enthält das SlideText-Array, das den Rohtext der Folien darstellt

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) Methode


Ruft den Rohtext aus den Folien ab

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Eingabestream |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraktionsmodus |

### Rückgabewert

Die Instanz von [PresentationText](../../presentationtext/) enthält das SlideText-Array, das den Rohtext der Folien darstellt

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) Methode


Ruft den Rohtext aus den Folien ab

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Eingabestream |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraktionsmodus |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Ladeoptionen |

### Rückgabewert

Die Instanz von [PresentationText](../../presentationtext/) enthält das SlideText-Array, das den Rohtext der Folien darstellt

## Siehe auch

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPresentationText](../../ipresentationtext/)
* Klasse [String](../../../system/string/)
* Klasse [PresentationFactory](../)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [ILoadOptions](../../iloadoptions/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)