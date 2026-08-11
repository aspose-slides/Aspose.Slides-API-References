---
title: Equals()
second_title: Aspose.Slides للـ C++ مرجع API
description: يحدد ما إذا كانت مثيلتا IBaseSlide متساويتين. تُحسب القيمة المرتجعة بناءً على بنية الشريحة والمحتوى الثابت. تكون الشريحتان متساويتين إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى وما إلى ذلك متساوية. لا تأخذ المقارنة في الاعتبار قيم المعرفات الفريدة، مثل SlideId والمحتوى الديناميكي، مثل قيمة التاريخ الحالية في العنصر النائب للـ Date.
type: docs
weight: 170
url: /ar/aspose.slides/baseslide/equals/
---
## BaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) طريقة


يحدد ما إذا كانت مثيلتا [IBaseSlide](../../ibaseslide/) متساويتين. تُحسب القيمة المرتجعة بناءً على بنية الشريحة والمحتوى الثابت. تكون الشريحتان متساويتين إذا كانت جميع الأشكال والأنماط والنصوص والرسوم المتحركة والإعدادات الأخرى وغيرها متساوية. لا تأخذ المقارنة في الاعتبار قيم المعرفات الفريدة، مثل SlideId والمحتوى الديناميكي، مثل قيمة التاريخ الحالية في Date [Placeholder](../../placeholder/).

```cpp
bool Aspose::Slides::BaseSlide::Equals(System::SharedPtr<IBaseSlide> slide) override
```


### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../ibaseslide/)\> | ال[IBaseSlide](../../ibaseslide/) للمقارنة مع الـ[IBaseSlide](../../ibaseslide/) الحالي. |

### قيمة الإرجاع

**true** إذا كان الـ[IBaseSlide](../../ibaseslide/) المحدد مساويًا للـ[IBaseSlide](../../ibaseslide/) الحالي؛ وإلا **false**.
## ملاحظات



المثال التالي يُظهر كيفية مقارنة شريحتين. 
```cpp
auto presentation1 = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto presentation2 = System::MakeObject<Presentation>(u"HelloWorld.pptx");
for (int32_t i = 0; i < presentation1->get_Masters()->get_Count(); i++)
{
    auto master1 = presentation1->get_Masters()->idx_get(i);
    for (int32_t j = 0; j < presentation2->get_Masters()->get_Count(); j++)
    {
        auto master2 = presentation2->get_Masters()->idx_get(j);
        if (System::ObjectExt::Equals(master1, master2))
        {
            System::Console::WriteLine(System::String::Format(u"SomePresentation1 MasterSlide#{0} is equal to SomePresentation2 MasterSlide#{1}", i, j));
        }
    }
}
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IBaseSlide](../../ibaseslide/)
* فئة [BaseSlide](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)