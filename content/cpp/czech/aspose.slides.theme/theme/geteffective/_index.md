---
title: GetEffective()
second_title: Aspose.Slides pro C++ API Reference
description: Získá účinná data motivu s aplikovanou dědičností.
type: docs
weight: 53
url: /cs/aspose.slides.theme/theme/geteffective/
---
## Theme::GetEffective() metoda

Získá účinná data motivu s aplikovanou dědičností.

```cpp
System::SharedPtr<IThemeEffectiveData> Aspose::Slides::Theme::Theme::GetEffective() override
```

### Návratová hodnota

A [IThemeEffectiveData](../../ithemeeffectivedata/).
## Poznámky

Tento příklad ukazuje, jak získat účinné vlastnosti motivu. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveTheme = pres->get_Slides()->idx_get(0)->get_ThemeManager()->get_OverrideTheme()->GetEffective();

Console::WriteLine(String(u"Font scheme name: ") + effectiveTheme->get_FontScheme()->get_Name());
Console::WriteLine(String(u"Major latin font: ") + effectiveTheme->get_FontScheme()->get_Major()->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Minor latin font: ") + effectiveTheme->get_FontScheme()->get_Minor()->get_LatinFont()->get_FontName());
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IThemeEffectiveData](../../ithemeeffectivedata/)
* třída [Theme](../)
* jmenný prostor [Aspose::Slides::Theme](../../)
* knihovna [Aspose.Slides](../../../)