---
title: GetAllTextFrames()
second_title: مرجع API Aspose.Slides للغة C++
description: يرجع جميع إطارات النص في عرض تقديمي بصيغة PPTX.
type: docs
weight: 79
url: /ar/aspose.slides.util/slideutil/getalltextframes/
---
## SlideUtil::GetAllTextFrames(System::SharedPtr\<IPresentation\>, bool) طريقة

يرجع جميع إطارات النص في عرض تقديمي بصيغة PPTX.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetAllTextFrames(System::SharedPtr<IPresentation> pres, bool withMasters)
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | العرض المفحوص. |
| withMasters | **bool** | يحدد ما إذا كان يجب فحص الشرائح الرئيسية. |

### قيمة الإرجاع

مصفوفة من كائنات [TextFrame](../../../aspose.slides/textframe/).

## انظر أيضا

* تعريف_نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف_نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ITextFrame](../../../aspose.slides/itextframe/)
* فئة [IPresentation](../../../aspose.slides/ipresentation/)
* فئة [SlideUtil](../)
* مساحة الاسم [Aspose::Slides::Util](../../)
* مكتبة [Aspose.Slides](../../../)