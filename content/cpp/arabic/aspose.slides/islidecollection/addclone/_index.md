---
title: AddClone()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: يضيف نسخة من شريحة محددة إلى نهاية المجموعة.
type: docs
weight: 14
url: /ar/aspose.slides/islidecollection/addclone/
---
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>) طريقة

يضيف نسخة من شريحة محددة إلى نهاية المجموعة.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide)=0
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) لتستنسخ. |

### قيمة الإرجاع

شريحة جديدة.

## ملاحظات

عند استنساخ شريحة بين عروض تقديمية مختلفة يمكن استنساخ الرئيس الخاص بالشريحة أيضًا. يُستخدم سجل داخلي لتتبع الرؤساء المستنسَخين تلقائيًا لمنع إنشاء نسخ متعددة من نفس شريحة الرئيس. لن يتم منع أو تسجيل الاستنساخ اليدوي لشريحة الرئيس. إذا كنت بحاجة إلى مزيد من التحكم في عملية الاستنساخ استخدم [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) أو [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) لاستنساخ الشرائح، و[IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) أو [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) لاستنساخ التخطيطات، و[IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) لاستنساخ الرؤساء.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) طريقة

يضيف نسخة من شريحة محددة إلى نهاية القسم المحدد.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section)=0
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) لتستنسخ. |
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

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) طريقة

يضيف نسخة من شريحة محددة إلى نهاية المجموعة.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) لتستنسخ. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | شريحة تخطيط لشريحة جديدة. |

### قيمة الإرجاع

شريحة جديدة.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) طريقة

يضيف نسخة من شريحة مصدر محددة إلى نهاية المجموعة. سيتم اختيار التخطيط المناسب تلقائيًا من الرئيس المحدد (التخطيط المناسب هو التخطيط الذي له نفس النوع أو الاسم كما في تخطيط الشريحة المصدر). إذا لم يكن هناك تخطيط مناسب، فسيتم استنساخ تخطيط الشريحة المصدر (إذا كان allowCloneMissingLayout صحيحًا) أو سيتم إلقاء استثناء PptxEditException (إذا كان allowCloneMissingLayout خطأ).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) لتستنسخ. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | شريحة رئيسية لشريحة جديدة. |
| allowCloneMissingLayout | **bool** | إذا لم يكن هناك تخطيط مناسب في الرئيس المحدد، فسيتم استنساخ تخطيط الشريحة المصدر (إذا كان allowCloneMissingLayout صحيحًا) أو سيتم إلقاء استثناء PptxEditException (إذا كان allowCloneMissingLayout خطأ). |

### قيمة الإرجاع

شريحة جديدة.

## انظر أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [ISlideCollection](../)
* Class [ISection](../../isection/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)