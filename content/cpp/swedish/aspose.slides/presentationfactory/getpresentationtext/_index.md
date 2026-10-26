---
title: GetPresentationText()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar den råa texten från bilderna
type: docs
weight: 53
url: /sv/aspose.slides/presentationfactory/getpresentationtext/
---
## PresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) method


Hämtar den råa texten från bilderna

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode) override
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Inmatningsfil |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraktionsläge |

### Returvärde

Instansen av [PresentationText](../../presentationtext/) som innehåller SlideText-arrayen som representerar den råa bildtexten

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) method


Hämtar den råa texten från bilderna

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode) override
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Indataström |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraktionsläge |

### Returvärde

Instansen av [PresentationText](../../presentationtext/) som innehåller SlideText-arrayen som representerar den råa bildtexten

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) method


Hämtar den råa texten från bilderna

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options) override
```


### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Indataström |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraktionsläge |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Laddningsalternativ |

### Returvärde

Instansen av [PresentationText](../../presentationtext/) som innehåller SlideText-arrayen som representerar den råa bildtexten

## Se även

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IPresentationText](../../ipresentationtext/)
* Klass [String](../../../system/string/)
* Klass [PresentationFactory](../)
* Klass [Stream](../../../system.io/stream/)
* Klass [ILoadOptions](../../iloadoptions/)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)