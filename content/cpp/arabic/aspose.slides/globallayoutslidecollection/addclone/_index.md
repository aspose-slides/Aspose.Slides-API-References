---
title: AddClone()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف نسخة من شريحة تخطيط محددة إلى العرض التقديمي.
type: docs
weight: 1
url: /ar/aspose.slides/globallayoutslidecollection/addclone/
---
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) طريقة

يضيف نسخة من شريحة تخطيط محددة إلى العرض التقديمي.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) للنسخ. |

### قيمة الإرجاع

الشريحة المضافة.

## ملاحظات

عند نسخ تخطيط بين عروض تقديمية مختلفة يمكن نسخ رئيس التخطيط أيضًا للحفاظ على تنسيق المصدر. يتم استخدام سجل داخلي لتتبع الرؤساء التي تم نسخها تلقائيًا لمنع إنشاء نسخ متعددة من نفس شريحة الرئيس. النسخ اليدوي لشريحة الرئيس لن يتم منعها ولا تسجيلها. 

## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) طريقة

يضيف نسخة من شريحة تخطيط محددة إلى العرض التقديمي.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) للنسخ. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | الشريحة الرئيسية لتخطيط جديد. |

### قيمة الإرجاع

الشريحة المضافة.

## ملاحظات

1) سيتم ربط التخطيط الجديد بالرئيس المحدد في العرض التقديمي الوجهة. لذا فإن ذلك يشبه النسخ/اللصق مع الخيار \"استخدام سمة الوجهة\" في PowerPoint.  
2) نظير هذه الطريقة هو طريقة [IMasterLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../imasterlayoutslidecollection/addclone/) يتم الوصول إليها عبر خاصية [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/).

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ILayoutSlide](../../ilayoutslide/)
* فئة [GlobalLayoutSlideCollection](../)
* فئة [IMasterSlide](../../imasterslide/)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)