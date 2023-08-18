---
title: GetPresentationText()
second_title: Aspose.Slides for C++ API Reference
description: Retrieves the raw text from the slides
type: docs
weight: 53
url: /aspose.slides/presentationfactory/getpresentationtext/
---
## PresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) method


Retrieves the raw text from the slides

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Input file |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraction mode |

### Return Value

The instance of [PresentationText](../../presentationtext/) containing the SlideText array representing the raw slides text

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) method


Retrieves the raw text from the slides

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Input stream |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraction mode |

### Return Value

The instance of [PresentationText](../../presentationtext/) containing the SlideText array representing the raw slides text

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) method


Retrieves the raw text from the slides

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options) override
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

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationText](../../ipresentationtext/)
* Class [String](../../../system/string/)
* Class [PresentationFactory](../)
* Class [Stream](../../../system.io/stream/)
* Class [ILoadOptions](../../iloadoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)