---
title: GetEffective()
second_title: مرجع API Aspose.Slides برای C++
description: داده‌های تم مؤثر را با اعمال ارث‌بری دریافت می‌کند.
type: docs
weight: 53
url: /fa/aspose.slides.theme/theme/geteffective/
---
## Theme::GetEffective() متد

داده‌های تم مؤثر را با اعمال ارث‌بری دریافت می‌کند.

```cpp
System::SharedPtr<IThemeEffectiveData> Aspose::Slides::Theme::Theme::GetEffective() override
```

### مقدار بازگشت

یک [IThemeEffectiveData](../../ithemeeffectivedata/).
## نکات

این مثال نحوه دریافت ویژگی‌های مؤثر تم را نشان می‌دهد. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveTheme = pres->get_Slides()->idx_get(0)->get_ThemeManager()->get_OverrideTheme()->GetEffective();

Console::WriteLine(String(u"Font scheme name: ") + effectiveTheme->get_FontScheme()->get_Name());
Console::WriteLine(String(u"Major latin font: ") + effectiveTheme->get_FontScheme()->get_Major()->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Minor latin font: ") + effectiveTheme->get_FontScheme()->get_Minor()->get_LatinFont()->get_FontName());
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IThemeEffectiveData](../../ithemeeffectivedata/)
* کلاس [Theme](../)
* فضای‌نام [Aspose::Slides::Theme](../../)
* کتابخانه [Aspose.Slides](../../../)