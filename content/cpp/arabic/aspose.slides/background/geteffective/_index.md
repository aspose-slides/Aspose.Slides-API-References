---
title: GetEffective()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحصل على بيانات الخلفية الفعالة مع تطبيق الوراثة.
type: docs
weight: 118
url: /ar/aspose.slides/background/geteffective/
---
## Background::GetEffective() طريقة


يحصل على بيانات الخلفية الفعالة مع تطبيق الوراثة.

```cpp
System::SharedPtr<IBackgroundEffectiveData> Aspose::Slides::Background::GetEffective() override
```


### قيمة الإرجاع

‏[IBackgroundEffectiveData](../../ibackgroundeffectivedata/).
## ملاحظات



يوضح هذا المثال الحصول على خصائص الخلفية الفعالة. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveBackground = pres->get_Slides()->idx_get(0)->get_Background()->GetEffective();
Console::WriteLine(String(u"Background fill type: ") + ObjectExt::ToString(effectiveBackground->get_FillFormat()->get_FillType()));
Console::WriteLine(String(u"Any effects applied: ") + !effectiveBackground->get_EffectFormat()->get_IsNoEffects());
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)
* فئة [Background](../)
* نطاق اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)