---
title: GetEffective()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على بيانات تنسيق الخط الفعّالة مع تطبيق الوراثة.
type: docs
weight: 417
url: /ar/aspose.slides/lineformat/geteffective/
---
## LineFormat::GetEffective() طريقة

يحصل على بيانات تنسيق الخط الفعّالة مع تطبيق الوراثة.

```cpp
System::SharedPtr<ILineFormatEffectiveData> Aspose::Slides::LineFormat::GetEffective() override
```

### قيمة الإرجاع

‏[ILineFormatEffectiveData](../../ilineformateffectivedata/).

## ملاحظات

يوضح هذا المثال الحصول على خصائص تنسيق الخط الفعّال للشكل. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveLineFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_LineFormat()->GetEffective();

Console::WriteLine(String(u"Style: ") + ObjectExt::ToString(effectiveLineFormat->get_Style()));
Console::WriteLine(String(u"Width: ") + effectiveLineFormat->get_Width());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectiveLineFormat->get_FillFormat()->get_FillType()));
```

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* الفئة [ILineFormatEffectiveData](../../ilineformateffectivedata/)
* الفئة [LineFormat](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)