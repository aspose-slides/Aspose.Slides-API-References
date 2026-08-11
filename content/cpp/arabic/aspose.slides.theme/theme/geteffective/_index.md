---
title: GetEffective()
second_title: Aspose.Slides لمرجع API C++
description: يحصل على بيانات السمة الفعالة مع تطبيق الوراثة.
type: docs
weight: 53
url: /ar/aspose.slides.theme/theme/geteffective/
---
## Theme::GetEffective() طريقة


يحصل على بيانات السمة الفعالة مع تطبيق الوراثة.

```cpp
System::SharedPtr<IThemeEffectiveData> Aspose::Slides::Theme::Theme::GetEffective() override
```


### قيمة الإرجاع

‏[IThemeEffectiveData](../../ithemeeffectivedata/).
## ملاحظات



يوضح هذا المثال الحصول على خصائص السمة الفعالة. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveTheme = pres->get_Slides()->idx_get(0)->get_ThemeManager()->get_OverrideTheme()->GetEffective();

Console::WriteLine(String(u"Font scheme name: ") + effectiveTheme->get_FontScheme()->get_Name());
Console::WriteLine(String(u"Major latin font: ") + effectiveTheme->get_FontScheme()->get_Major()->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Minor latin font: ") + effectiveTheme->get_FontScheme()->get_Minor()->get_LatinFont()->get_FontName());
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IThemeEffectiveData](../../ithemeeffectivedata/)
* فئة [Theme](../)
* نطاق [Aspose::Slides::Theme](../../)
* مكتبة [Aspose.Slides](../../../)