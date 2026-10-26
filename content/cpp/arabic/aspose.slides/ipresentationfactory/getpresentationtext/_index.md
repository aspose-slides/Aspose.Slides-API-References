---
title: GetPresentationText()
second_title: Aspose.Slides لواجهة برمجة تطبيقات C++
description: يسترجع النص الخام من الشرائح
type: docs
weight: 40
url: /ar/aspose.slides/ipresentationfactory/getpresentationtext/
---
## IPresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) طريقة

تسترجع النص الخام من الشرائح

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode)=0
```

### المعلمات

| معلمة | نوع | وصف |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | ملف الإدخال |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | وضع الاستخراج |

### قيمة الإرجاع

مثيل [PresentationText](../../presentationtext/) يحتوي على مصفوفة SlideText التي تمثل النص الخام للشرائح

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) طريقة

تسترجع النص الخام من الشرائح

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode)=0
```

### المعلمات

| معلمة | نوع | وصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | دفق الإدخال |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | وضع الاستخراج |

### قيمة الإرجاع

مثيل [PresentationText](../../presentationtext/) يحتوي على مصفوفة SlideText التي تمثل النص الخام للشرائح

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) طريقة

تسترجع النص الخام من الشرائح

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options)=0
```

### المعلمات

| معلمة | نوع | وصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | دفق الإدخال |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | وضع الاستخراج |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | خيارات التحميل |

### قيمة الإرجاع

مثيل [PresentationText](../../presentationtext/) يحتوي على مصفوفة SlideText التي تمثل النص الخام للشرائح

## انظر أيضًا

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationText](../../ipresentationtext/)
* Class [String](../../../system/string/)
* Class [IPresentationFactory](../)
* Class [Stream](../../../system.io/stream/)
* Class [ILoadOptions](../../iloadoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)