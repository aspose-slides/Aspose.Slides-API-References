---
title: GetPresentationText()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft den rohen Text aus den Folien ab
type: docs
weight: 40
url: /de/aspose.slides/ipresentationfactory/getpresentationtext/
---
## IPresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) Methode


Ruft den rohen Text aus den Folien ab

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Eingabedatei |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraktionsmodus |

### Rückgabewert

Die Instanz von [PresentationText](../../presentationtext/) enthält das SlideText-Array, das den rohen Folientext darstellt

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) Methode


Ruft den rohen Text aus den Folien ab

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Eingabestream |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraktionsmodus |

### Rückgabewert

Die Instanz von [PresentationText](../../presentationtext/) enthält das SlideText-Array, das den rohen Folientext darstellt

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) Methode


Ruft den rohen Text aus den Folien ab

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Eingabestream |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraktionsmodus |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Ladeoptionen |

### Rückgabewert

Die Instanz von [PresentationText](../../presentationtext/) enthält das SlideText-Array, das den rohen Folientext darstellt

## Siehe auch

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPresentationText](../../ipresentationtext/)
* Klasse [String](../../../system/string/)
* Klasse [IPresentationFactory](../)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [ILoadOptions](../../iloadoptions/)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)