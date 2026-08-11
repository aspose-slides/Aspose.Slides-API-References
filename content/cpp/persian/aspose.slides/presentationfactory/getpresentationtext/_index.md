---
title: GetPresentationText()
second_title: مرجع API Aspose.Slides برای C++
description: متن خام اسلایدها را دریافت می‌کند
type: docs
weight: 53
url: /fa/aspose.slides/presentationfactory/getpresentationtext/
---
## PresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) متد


متن خام اسلایدها را دریافت می‌کند

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode) override
```


### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Input file |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraction mode |

### مقدار بازگشت

نمونه‌ای از [PresentationText](../../presentationtext/) که شامل آرایه SlideText است و متن خام اسلایدها را نشان می‌دهد

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) متد


متن خام اسلایدها را دریافت می‌کند

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode) override
```


### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Input stream |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraction mode |

### مقدار بازگشت

نمونه‌ای از [PresentationText](../../presentationtext/) که شامل آرایه SlideText است و متن خام اسلایدها را نشان می‌دهد

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) متد


متن خام اسلایدها را دریافت می‌کند

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options) override
```


### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Input stream |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Extraction mode |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Load options |

### مقدار بازگشت

نمونه‌ای از [PresentationText](../../presentationtext/) که شامل آرایه SlideText است و متن خام اسلایدها را نشان می‌دهد

## موارد مرتبط

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationText](../../ipresentationtext/)
* Class [String](../../../system/string/)
* Class [PresentationFactory](../)
* Class [Stream](../../../system.io/stream/)
* Class [ILoadOptions](../../iloadoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)