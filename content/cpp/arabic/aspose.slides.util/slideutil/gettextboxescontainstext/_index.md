---
title: GetTextBoxesContainsText()
second_title: مرجع API Aspose.Slides للغة C++
description: يعيد جميع إطارات النص في الشريحة المحددة التي تحتوي على النص المعطى.
type: docs
weight: 66
url: /ar/aspose.slides.util/slideutil/gettextboxescontainstext/
---
## SlideUtil::GetTextBoxesContainsText(System::SharedPtr\<IBaseSlide\>, System::String, bool) طريقة

يرجع جميع إطارات النص في الشريحة المحددة التي تحتوي على النص المعطى.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetTextBoxesContainsText(System::SharedPtr<IBaseSlide> slide, System::String text, bool checkPlaceholderText)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | الشريحة للبحث عنها. |
| text | [System::String](../../../system/string/) | النص المراد البحث عنه داخل إطارات النص. |
| checkPlaceholderText | **bool** | يشير إلى ما إذا كان يجب تضمين إطارات النص الفارغة، ولكن التي يحتوي نص العنصر النائب فيها على النص المطلوب البحث عنه. |

### قيمة الإرجاع

مصفوفة من كائنات [ITextFrame](../../../aspose.slides/itextframe/) التي تحتوي على النص المحدد.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ITextFrame](../../../aspose.slides/itextframe/)
* فئة [IBaseSlide](../../../aspose.slides/ibaseslide/)
* فئة [String](../../../system/string/)
* فئة [SlideUtil](../)
* مساحة الاسم [Aspose::Slides::Util](../../)
* مكتبة [Aspose.Slides](../../../)