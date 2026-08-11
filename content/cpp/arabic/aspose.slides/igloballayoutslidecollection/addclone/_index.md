---
title: AddClone()
second_title: مرجع API Aspose.Slides للغة C++
description: يضيف نسخة من شريحة التخطيط المحددة إلى العرض التقديمي.
type: docs
weight: 1
url: /ar/aspose.slides/igloballayoutslidecollection/addclone/
---
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) method

يضيف نسخة من شريحة تخطيط محددة إلى العرض التقديمي.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) للاستنساخ. |

### قيمة الإرجاع

الشريحة المضافة.

## ملاحظات

عند استنساخ تخطيط بين عروض تقديمية مختلفة يمكن استنساخ ماستر التخطيط أيضًا للحفاظ على تنسيق المصدر. يتم استخدام سجل داخلي لتتبع الماسترات المستنسخة تلقائيًا لمنع إنشاء نسخ متعددة من نفس شريحة الماستر. لن يتم منع أو تسجيل الاستنساخ اليدوي لشرائح الماستر.

## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) method

يضيف نسخة من شريحة تخطيط محددة إلى العرض التقديمي.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster)=0
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) للاستنساخ. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | شريحة الماستر لتخطيط جديد. |

### قيمة الإرجاع

الشريحة المضافة.

## ملاحظات

سيتم ربط التخطيط الجديد بالماستر المحدد في عرض الوجهة. وبالتالي هذا يشبه عملية النسخ/اللصق مع "Use Destination Theme" في PowerPoint.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* صنف [ILayoutSlide](../../ilayoutslide/)
* صنف [IGlobalLayoutSlideCollection](../)
* صنف [IMasterSlide](../../imasterslide/)
* فضاء الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)