---
title: GetEffective()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar effektiv temadata med arv tillämpat.
type: docs
weight: 53
url: /sv/aspose.slides.theme/theme/geteffective/
---
## Theme::GetEffective() metod


Hämtar effektiv temadata med arv tillämpat.

```cpp
System::SharedPtr<IThemeEffectiveData> Aspose::Slides::Theme::Theme::GetEffective() override
```


### Returvärde

En [IThemeEffectiveData](../../ithemeeffectivedata/).
## Anmärkningar



Detta exempel visar hur man hämtar effektiva temaegenskaper. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveTheme = pres->get_Slides()->idx_get(0)->get_ThemeManager()->get_OverrideTheme()->GetEffective();

Console::WriteLine(String(u"Font scheme name: ") + effectiveTheme->get_FontScheme()->get_Name());
Console::WriteLine(String(u"Major latin font: ") + effectiveTheme->get_FontScheme()->get_Major()->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Minor latin font: ") + effectiveTheme->get_FontScheme()->get_Minor()->get_LatinFont()->get_FontName());
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IThemeEffectiveData](../../ithemeeffectivedata/)
* Klass [Theme](../)
* Namnrymd [Aspose::Slides::Theme](../../)
* Bibliotek [Aspose.Slides](../../../)