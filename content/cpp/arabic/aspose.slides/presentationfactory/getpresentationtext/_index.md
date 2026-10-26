---
title: GetPresentationText()
second_title: Aspose.Slides لـ C++ مرجع API
description: يسترجع النص الخام من الشرائح
type: docs
weight: 53
url: /ar/aspose.slides/presentationfactory/getpresentationtext/
---
## PresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) method

يسترجع النص الخام من الشرائح

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | ملف الإدخال |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | وضع الاستخراج |

### قيمة الإرجاع

الكائن من نوع [PresentationText](../../presentationtext/) يحتوي على مصفوفة SlideText التي تمثل النص الخام للشرائح

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) method

يسترجع النص الخام من الشرائح

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | دفق الإدخال |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | وضع الاستخراج |

### قيمة الإرجاع

الكائن من نوع [PresentationText](../../presentationtext/) يحتوي على مصفوفة SlideText التي تمثل النص الخام للشرائح

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) method

يسترجع النص الخام من الشرائح

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | دفق الإدخال |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | وضع الاستخراج |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | خيارات التحميل |

### قيمة الإرجاع

الكائن من نوع [PresentationText](../../presentationtext/) يحتوي على مصفوفة SlideText التي تمثل النص الخام للشرائح

## انظر أيضًا

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationText](../../ipresentationtext/)
* Class [String](../../../system/string/)
* Class [PresentationFactory](../)
* Class [Stream](../../../system.io/stream/)
* Class [ILoadOptions](../../iloadoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)