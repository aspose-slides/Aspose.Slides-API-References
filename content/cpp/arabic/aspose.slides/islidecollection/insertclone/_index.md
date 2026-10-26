---
title: InsertClone()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يقوم بإدراج نسخة من شريحة محددة في الموضع المحدد داخل المجموعة.
type: docs
weight: 27
url: /ar/aspose.slides/islidecollection/insertclone/
---
## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) method

يقوم بإدراج نسخة من الشريحة المحددة في الموضع المحدد داخل المجموعة.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | فهرس الشريحة الجديدة. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) للاستنساخ. |

### قيمة الإرجاع

الشريحة المدخلة.

## ملاحظات

عند استنساخ شريحة بين عروض تقديمية مختلفة يمكن أيضًا استنساخ ماستر الشريحة. يتم استخدام سجل داخلي لتتبع الماسترات المستنساخة تلقائيًا لمنع إنشاء نسخ متعددة من نفس شريحة الماستر. لن يتم منع أو تسجيل الاستنساخ اليدوي لشرائح الماستر. إذا كنت بحاجة إلى مزيد من التحكم في عملية الاستنساخ استخدم [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) أو [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) لاستنساخ الشرائح و[IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) لاستنساخ الماسترات. 

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) method

يقوم بإدراج نسخة من الشريحة المحددة في الموضع المحدد داخل المجموعة.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | فهرس الشريحة الجديدة. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) للاستنساخ. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | شريحة تخطيط لشريحة جديدة. |

### قيمة الإرجاع

الشريحة المدخلة.

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) method

يقوم بإدراج نسخة من شريحة المصدر المحددة في الموضع المحدد داخل المجموعة. سيتم اختيار التخطيط المناسب تلقائيًا من الماستر المحدد (التخطيط المناسب هو التخطيط الذي يملك نفس النوع أو الاسم كما في تخطيط شريحة المصدر). إذا لم يكن هناك تخطيط مناسب فإن تخطيط شريحة المصدر سيُستنسخ (إذا كان allowCloneMissingLayout صحيحًا) أو سيتم رمي استثناء PptxEditException (إذا كان allowCloneMissingLayout خاطئًا).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | فهرس الشريحة الجديدة. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) للاستنساخ. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | شريحة ماستر لشريحة جديدة. |
| allowCloneMissingLayout | **bool** | إذا لم يكن هناك تخطيط مناسب في الماستر المحدد فإن تخطيط شريحة المصدر سيُستنسخ (إذا كان allowCloneMissingLayout صحيحًا) أو سيتم رمي استثناء PptxEditException (إذا كان allowCloneMissingLayout خاطئًا). |

### قيمة الإرجاع

الشريحة المدخلة.

## أنظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ISlide](../../islide/)
* فئة [ISlideCollection](../)
* فئة [ILayoutSlide](../../ilayoutslide/)
* فئة [IMasterSlide](../../imasterslide/)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)