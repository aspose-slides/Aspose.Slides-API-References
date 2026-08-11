---
title: InsertClone()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بإدراج نسخة من شريحة محددة إلى الموضع المحدد في المجموعة.
type: docs
weight: 66
url: /ar/aspose.slides/slidecollection/insertclone/
---
## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) طريقة

يقوم بإدراج نسخة من شريحة محددة إلى الموضع المحدد في المجموعة.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | فهرس الشريحة الجديدة. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) للنسخ. |

### قيمة الإرجاع

الشريحة المدخلة.

## ملاحظات

عند استنساخ شريحة بين عروض تقديمية مختلفة يمكن استنساخ ماستر الشريحة أيضًا. يُستخدم سجل داخلي لتتبع الماسترات المستنسخة تلقائيًا لمنع إنشاء نسخ متعددة من نفس شريحة الماستر. لن يتم منع أو تسجيل الاستنساخ اليدوي لشرائح الماستر. إذا كنت بحاجة إلى مزيد من التحكم في عملية الاستنساخ، استخدم [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/insertclone/) أو [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/insertclone/) لاستنساخ الشرائح و[IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) لاستنساخ الماسترات.

يوضح المثال التالي كيفية الاستنساخ في موضع آخر داخل [Presentation](../../presentation/).
```cpp
// إنشاء كائن من فئة Presentation التي تمثل ملف عرض تقديمي
auto pres = System::MakeObject<Presentation>(u"CloneWithInSamePresentation.pptx");

// استنساخ الشريحة المطلوبة إلى نهاية مجموعة الشرائح في العرض التقديمي نفسه
System::SharedPtr<ISlideCollection> slides = pres->get_Slides();
// استنساخ الشريحة المطلوبة إلى الفهرس المحدد في العرض التقديمي نفسه
slides->InsertClone(2, slides->idx_get(1));
// كتابة العرض التقديمي المعدل إلى القرص
pres->Save(u"Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat::Pptx);
```
يوضح المثال التالي كيفية الاستنساخ في موضع آخر داخل [Presentation](../../presentation/).
```cpp
// إنشاء فئة Presentation لتحميل ملف العرض التقديمي المصدر
auto srcPres = System::MakeObject<Presentation>(u"CloneAtEndOfAnother.pptx");

// إنشاء فئة Presentation لملف PPTX الوجهة (حيث سيتم استنساخ الشريحة)
auto destPres = System::MakeObject<Presentation>();

destPres->get_Slides()->InsertClone(2, srcPres->get_Slides()->idx_get(0));
// كتابة العرض التقديمي الوجهة إلى القرص
destPres->Save(u"Aspose2_out.pptx", SaveFormat::Pptx);
```

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) طريقة

يقوم بإدراج نسخة من شريحة محددة إلى الموضع المحدد في المجموعة.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | فهرس الشريحة الجديدة. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) للنسخ. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | شريحة تخطيط للشريحة الجديدة. |

### قيمة الإرجاع

الشريحة المدخلة.

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) طريقة

يقوم بإدراج نسخة من شريحة مصدر محددة إلى الموضع المحدد في المجموعة. سيتم اختيار التخطيط المناسب تلقائيًا من الماستر المحدد (التخطيط المناسب هو التخطيط الذي له نفس النوع أو الاسم مثل تخطيط شريحة المصدر). إذا لم يكن هناك تخطيط مناسب فسيتم استنساخ تخطيط شريحة المصدر (إذا كان allowCloneMissingLayout صحيحًا) أو سيتم إثارة استثناء PptxEditException (إذا كان allowCloneMissingLayout خاطئًا).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | فهرس الشريحة الجديدة. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) للنسخ. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | شريحة ماستر لشريحة جديدة. |
| allowCloneMissingLayout | **bool** | إذا لم يكن هناك تخطيط مناسب في الماستر المحدد، فسيتم استنساخ تخطيط شريحة المصدر (إذا كان allowCloneMissingLayout صحيحًا) أو سيتم إثارة استثناء PptxEditException (إذا كان allowCloneMissingLayout خاطئًا). |

### قيمة الإرجاع

الشريحة المدخلة.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [SlideCollection](../)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)