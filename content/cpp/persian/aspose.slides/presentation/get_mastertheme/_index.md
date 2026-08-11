---
title: get_MasterTheme()
second_title: مرجع API برای Aspose.Slides به C++
description: "تم اصلی را برمی‌گرداند. فقط خواندنی Theme::IMasterTheme."
type: docs
weight: 404
url: /fa/aspose.slides/presentation/get_mastertheme/
---
## Presentation::get_MasterTheme() متد

تم اصلی را برمی‌گرداند. فقط خواندنی [Theme::IMasterTheme](../../../aspose.slides.theme/imastertheme/).

```cpp
System::SharedPtr<Theme::IMasterTheme> Aspose::Slides::Presentation::get_MasterTheme() override
```

## ملاحظات

نمونه‌های زیر نشان می‌دهند چگونه با تغییر بخش‌هایی از عناصر PowerPoint [Presentation](../) می‌توان اثر تم را تغییر داد.
```cpp
// یک شیء ارائه که نمایانگر یک فایل ارائه است را نمونه‌سازی کنید
auto pres = System::MakeObject<Presentation>(u"Subtle_Moderate_Intense.pptx");
auto masterTheme = pres->get_MasterTheme();
auto formatScheme = masterTheme->get_FormatScheme();

formatScheme->get_LineStyles()->idx_get(0)->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
formatScheme->get_FillStyles()->idx_get(2)->set_FillType(FillType::Solid);
formatScheme->get_FillStyles()->idx_get(2)->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
formatScheme->get_EffectStyles()->idx_get(2)->get_EffectFormat()->get_OuterShadowEffect()->set_Distance(10.0f);
pres->Save(u"Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMasterTheme](../../../aspose.slides.theme/imastertheme/)
* کلاس [Presentation](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)