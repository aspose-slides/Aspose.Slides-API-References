---
title: GetEffective()
second_title: Aspose.Slides C++ API referencia
description: Lekéri a hatékony témadatokat az öröklődés alkalmazásával.
type: docs
weight: 53
url: /hu/aspose.slides.theme/theme/geteffective/
---
## Theme::GetEffective() metódus

Lekéri a hatékony témadatokat a öröklődés alkalmazásával.

```cpp
System::SharedPtr<IThemeEffectiveData> Aspose::Slides::Theme::Theme::GetEffective() override
```


### Visszatérési érték

A [IThemeEffectiveData](../../ithemeeffectivedata/).
## Megjegyzések



Ez a példa bemutatja a hatékony témajellemzők lekérését. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveTheme = pres->get_Slides()->idx_get(0)->get_ThemeManager()->get_OverrideTheme()->GetEffective();

Console::WriteLine(String(u"Font scheme name: ") + effectiveTheme->get_FontScheme()->get_Name());
Console::WriteLine(String(u"Major latin font: ") + effectiveTheme->get_FontScheme()->get_Major()->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Minor latin font: ") + effectiveTheme->get_FontScheme()->get_Minor()->get_LatinFont()->get_FontName());
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IThemeEffectiveData](../../ithemeeffectivedata/)
* Osztály [Theme](../)
* Névtere [Aspose::Slides::Theme](../../)
* Könyvtár [Aspose.Slides](../../../)