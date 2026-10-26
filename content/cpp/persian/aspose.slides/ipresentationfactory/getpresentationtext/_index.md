---
title: GetPresentationText()
second_title: مرجع API Aspose.Slides برای C++
description: متن خام اسلایدها را بازیابی می‌کند
type: docs
weight: 40
url: /fa/aspose.slides/ipresentationfactory/getpresentationtext/
---
## IPresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) متد

متن خام اسلایدها را بازیابی می‌کند

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | فایل ورودی |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | حالت استخراج |

### مقدار بازگشت

نمونه‌ای از [PresentationText](../../presentationtext/) که شامل آرایهٔ SlideText است که متن خام اسلایدها را نشان می‌دهد

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) متد

متن خام اسلایدها را بازیابی می‌کند

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریان ورودی |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | حالت استخراج |

### مقدار بازگشت

نمونه‌ای از [PresentationText](../../presentationtext/) که شامل آرایهٔ SlideText است که متن خام اسلایدها را نشان می‌دهد

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) متد

متن خام اسلایدها را بازیابی می‌کند

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریان ورودی |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | حالت استخراج |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | گزینه‌های بارگذاری |

### مقدار بازگشت

نمونه‌ای از [PresentationText](../../presentationtext/) که شامل آرایهٔ SlideText است که متن خام اسلایدها را نشان می‌دهد

## See Also

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationText](../../ipresentationtext/)
* Class [String](../../../system/string/)
* Class [IPresentationFactory](../)
* Class [Stream](../../../system.io/stream/)
* Class [ILoadOptions](../../iloadoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)