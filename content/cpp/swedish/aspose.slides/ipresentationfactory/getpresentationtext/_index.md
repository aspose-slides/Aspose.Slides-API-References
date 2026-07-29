---
title: GetPresentationText()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar den råa texten från bilderna
type: docs
weight: 40
url: /sv/aspose.slides/ipresentationfactory/getpresentationtext/
---
## IPresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) metod


Hämtar den råa texten från bilderna

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Indatafil |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraheringsläge |

### Returvärde

Instansen av [PresentationText](../../presentationtext/) som innehåller SlideText-arrayen som representerar den råa texten i bilderna

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) metod


Hämtar den råa texten från bilderna

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Indataström |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraheringsläge |

### Returvärde

Instansen av [PresentationText](../../presentationtext/) som innehåller SlideText-arrayen som representerar den råa texten i bilderna

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) metod


Hämtar den råa texten från bilderna

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Indataström |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraheringsläge |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Laddningsalternativ |

### Returvärde

Instansen av [PresentationText](../../presentationtext/) som innehåller SlideText-arrayen som representerar den råa texten i bilderna

## Se även

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IPresentationText](../../ipresentationtext/)
* Klass [String](../../../system/string/)
* Klass [IPresentationFactory](../)
* Klass [Stream](../../../system.io/stream/)
* Klass [ILoadOptions](../../iloadoptions/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)