---
title: InsertClone()
second_title: Aspose.Slides للـ C++ مرجع واجهة برمجة التطبيقات
description: يُدرج نسخة من الشريحة الرئيسية المحددة في الموضع المحدد داخل المجموعة. سيتم نسخ الشرائح المرتبطة بالتخطيط أيضًا.
type: docs
weight: 105
url: /ar/aspose.slides/masterslidecollection/insertclone/
---
## MasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) طريقة


Inserts a copy of a specified master slide to specified position of the collection. Linked layout slides will be copied too.

```cpp
System::SharedPtr<IMasterSlide> Aspose::Slides::MasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | فهرس الشريحة الجديدة. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) للتكرار. |

### قيمة الإرجاع

الشريحة الرئيسية المدخلة.
## ملاحظات



المثال التالي يوضح كيفية استنساخ الشريحة الرئيسية في PowerPoint [Presentation](../../presentation/) آخر.
```cpp
// إنشاء كائن من فئة Presentation لتحميل ملف العرض المصدر
auto srcPres = System::MakeObject<Presentation>(u"CloneToAnotherPresentationWithMaster.pptx");

// إنشاء كائن من فئة Presentation للعرض الهدف (حيث سيتم استنساخ الشريحة)
auto destPres = System::MakeObject<Presentation>();

// إنشاء كائن ISlide من مجموعة الشرائح في العرض المصدر مع
// الشريحة الرئيسية
auto sourceSlide = srcPres->get_Slides()->idx_get(0);
auto sourceMaster = sourceSlide->get_LayoutSlide()->get_MasterSlide();
// الحصول على الشرائح الرئيسية للعرض الهدف
auto masters = destPres->get_Masters();
// استنساخ الشريحة الرئيسية المطلوبة من العرض المصدر إلى مجموعة الشرائح الرئيسية في ال
// العرض الهدف
System::SharedPtr<IMasterSlide> iSlide = masters->AddClone(sourceMaster);
// مجموعة الشرائح في العرض الهدف
auto slides = destPres->get_Slides();
// استنساخ الشريحة المصدر إلى مجموعة الشرائح في العرض الهدف.
slides->AddClone(sourceSlide, iSlide, true);
// حفظ العرض الهدف إلى القرص
destPres->Save(u"CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [IMasterSlide](../../imasterslide/)
* الفئة [MasterSlideCollection](../)
* المجال [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)