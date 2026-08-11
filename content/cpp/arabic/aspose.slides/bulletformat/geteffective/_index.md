---
title: GetEffective()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يجلب بيانات تنسيق النقاط الفعّالة مع تطبيق الوراثة.
type: docs
weight: 248
url: /ar/aspose.slides/bulletformat/geteffective/
---
## BulletFormat::GetEffective() طريقة


يجلب بيانات تنسيق النقاط الفعّالة مع تطبيق الوراثة.

```cpp
System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::BulletFormat::GetEffective() override
```


### قيمة الإرجاع

‏[IBulletFormatEffectiveData](../../ibulletformateffectivedata/).
## ملاحظات



هذا المثال يوضح كيفية الحصول على بعض خصائص تنسيق النقاط الفعّالة. 
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<Aspose::Slides::IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveBulletFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_Bullet()->GetEffective();

Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveBulletFormat->get_Type()));
if (effectiveBulletFormat->get_Type() == Aspose::Slides::BulletType::Numbered)
{
    Console::WriteLine(String(u"Numbered style: ") + ObjectExt::ToString(effectiveBulletFormat->get_NumberedBulletStyle()));
    Console::WriteLine(String(u"Starting number: ") + effectiveBulletFormat->get_NumberedBulletStartWith());
}
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* فئة [BulletFormat](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)