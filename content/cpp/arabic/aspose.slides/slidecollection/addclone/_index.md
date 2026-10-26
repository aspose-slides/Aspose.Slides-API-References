---
title: AddClone()
second_title: Aspose.Slides للغة C++ مرجع API
description: يضيف نسخة من شريحة محددة إلى نهاية المجموعة.
type: docs
weight: 53
url: /ar/aspose.slides/slidecollection/addclone/
---
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>) طريقة

يضيف نسخة من الشريحة المحددة إلى نهاية المجموعة.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide) override
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) لنسخ. |

### قيمة الإرجاع

شريحة جديدة.

## ملاحظات

عند نسخ شريحة بين عروض تقديمية مختلفة يمكن نسخ ماستر الشريحة أيضًا. يتم استخدام سجل داخلي لتتبع الماسترات المنسوخة تلقائيًا لمنع إنشاء نسخ متعددة من نفس شريحة الماستر. لا يتم منع أو تسجيل النسخ اليدوي لشاشات الماستر. إذا كنت تحتاج إلى مزيد من التحكم في عملية النسخ، استخدم [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/addclone/) أو [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/addclone/) لنسخ الشرائح، [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) أو [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) لنسخ التخطيطات و[IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) لنسخ الماسترات. 

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) طريقة

يضيف نسخة من الشريحة المحددة إلى نهاية القسم المحدد.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section) override
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) لنسخ. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) لشريحة جديدة. |

### قيمة الإرجاع

شريحة جديدة.

## ملاحظات

```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// الآن يحتوي القسم الثاني على نسخة من الشريحة الأولى.
```

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) طريقة

يضيف نسخة من الشريحة المحددة إلى نهاية المجموعة.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) لنسخ. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | شريحة تخطيط لشريحة جديدة. |

### قيمة الإرجاع

شريحة جديدة.

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) طريقة

يضيف نسخة من الشريحة المصدر المحددة إلى نهاية المجموعة. سيتم اختيار التخطيط المناسب تلقائيًا من الماستر المحدد (التخطيط المناسب هو التخطيط الذي يحمل نفس النوع أو الاسم كما في تخطيط الشريحة المصدر). إذا لم يتوفر تخطيط مناسب فسيتم نسخ تخطيط الشريحة المصدر (إذا كان allowCloneMissingLayout true) أو سيتم رمي استثناء PptxEditException (إذا كان allowCloneMissingLayout false).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) لنسخ. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | ماستر شريحة لشريحة جديدة. |
| allowCloneMissingLayout | **bool** | إذا لم يكن هناك تخطيط مناسب في الماستر المحدد، فسيتم نسخ تخطيط الشريحة المصدر (إذا كان allowCloneMissingLayout true) أو سيتم رمي استثناء PptxEditException (إذا كان allowCloneMissingLayout false). |

### قيمة الإرجاع

شريحة جديدة.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [SlideCollection](../)
* Class [ISection](../../isection/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)