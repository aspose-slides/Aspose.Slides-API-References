---
title: GetEffective()
second_title: مرجع API Aspose.Slides لـ C++
description: يحصل على بيانات تنسيق الفقرات النقطية الفعّالة مع تطبيق الوراثة.
type: docs
weight: 248
url: /ar/aspose.slides/ibulletformat/geteffective/
---
## IBulletFormat::GetEffective() طريقة

يحصل على بيانات تنسيق الفقرات النقطية الفعّالة مع تطبيق الوراثة.

```cpp
virtual System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::IBulletFormat::GetEffective()=0
```

### قيمة الإرجاع

كائن [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).
## ملاحظات

يوضح هذا المثال كيفية الحصول على بعض خصائص تنسيق الفقرات النقطية الفعّالة. 
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
* فئة [IBulletFormat](../)
* نطاق اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)