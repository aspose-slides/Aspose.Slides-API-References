---
title: GetPresentationText()
second_title: Aspose.Slides for C++ API Reference
description: Retrieves the raw text from the slides
type: docs
weight: 40
url: /cpp/aspose.slides/ipresentationfactory/getpresentationtext/
---
## IPresentationFactory::GetPresentationText([System::String](../../../system/string/), [TextExtractionArrangingMode](../../textextractionarrangingmode/)) method


Retrieves the raw text from the slides

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Input file |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraction mode |

### Return Value

The instance of [PresentationText](../../presentationtext/) containing the SlideText array representing the raw slides text

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationText](../../ipresentationtext/)
* Class [String](../../../system/string/)
* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Class [IPresentationFactory](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IPresentationFactory::GetPresentationText([System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>, [TextExtractionArrangingMode](../../textextractionarrangingmode/)) method


Retrieves the raw text from the slides

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Input stream |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraction mode |

### Return Value

The instance of [PresentationText](../../presentationtext/) containing the SlideText array representing the raw slides text

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationText](../../ipresentationtext/)
* Class [Stream](../../../system.io/stream/)
* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Class [IPresentationFactory](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## IPresentationFactory::GetPresentationText([System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>, [TextExtractionArrangingMode](../../textextractionarrangingmode/), [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\>) method


Retrieves the raw text from the slides

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Input stream |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraction mode |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Load options |

### Return Value

The instance of [PresentationText](../../presentationtext/) containing the SlideText array representing the raw slides text

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationText](../../ipresentationtext/)
* Class [Stream](../../../system.io/stream/)
* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Class [ILoadOptions](../../iloadoptions/)
* Class [IPresentationFactory](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
