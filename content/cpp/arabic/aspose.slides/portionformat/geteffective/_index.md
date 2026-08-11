---
title: GetEffective()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على بيانات تنسيق الجزء الفعّالة مع تطبيق الوراثة.
type: docs
weight: 131
url: /ar/aspose.slides/portionformat/geteffective/
---
## PortionFormat::GetEffective() طريقة

يحصل على بيانات تنسيق الجزء الفعّالة مع تطبيق الوراثة.

```cpp
System::SharedPtr<IPortionFormatEffectiveData> Aspose::Slides::PortionFormat::GetEffective() override
```

### قيمة الإرجاع

[IPortionFormatEffectiveData](../../iportionformateffectivedata/).

## ملاحظات

يوضح هذا المثال الحصول على بعض خصائص تنسيق الجزء الفعّالة.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectivePortionFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)->get_PortionFormat()->GetEffective();

Console::WriteLine(String(u"Latin font: ") + effectivePortionFormat->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Font height: ") + effectivePortionFormat->get_FontHeight());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectivePortionFormat->get_FillFormat()->get_FillType()));
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IPortionFormatEffectiveData](../../iportionformateffectivedata/)
* فئة [PortionFormat](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)