---
title: GetEffective()
second_title: Aspose.Slides C++ API Referansı
description: Kalıtım uygulanmış etkili tema verilerini alır.
type: docs
weight: 53
url: /tr/aspose.slides.theme/theme/geteffective/
---
## Theme::GetEffective() yöntemi


Kalıtım uygulanmış etkili tema verilerini alır.

```cpp
System::SharedPtr<IThemeEffectiveData> Aspose::Slides::Theme::Theme::GetEffective() override
```


### Dönüş Değeri

Bir [IThemeEffectiveData](../../ithemeeffectivedata/).
## Açıklamalar



Bu örnek, etkili tema özelliklerini almayı gösterir.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveTheme = pres->get_Slides()->idx_get(0)->get_ThemeManager()->get_OverrideTheme()->GetEffective();

Console::WriteLine(String(u"Font scheme name: ") + effectiveTheme->get_FontScheme()->get_Name());
Console::WriteLine(String(u"Major latin font: ") + effectiveTheme->get_FontScheme()->get_Major()->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Minor latin font: ") + effectiveTheme->get_FontScheme()->get_Minor()->get_LatinFont()->get_FontName());
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IThemeEffectiveData](../../ithemeeffectivedata/)
* Class [Theme](../)
* Namespace [Aspose::Slides::Theme](../../)
* Library [Aspose.Slides](../../../)