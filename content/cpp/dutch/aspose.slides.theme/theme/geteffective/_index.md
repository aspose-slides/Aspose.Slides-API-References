---
title: GetEffective()
second_title: Aspose.Slides voor C++ API Referentie
description: Haalt effectieve themagegevens op met de overerving toegepast.
type: docs
weight: 53
url: /nl/aspose.slides.theme/theme/geteffective/
---
## Theme::GetEffective() methode


Haalt effectieve themagegevens op met de overerving toegepast.

```cpp
System::SharedPtr<IThemeEffectiveData> Aspose::Slides::Theme::Theme::GetEffective() override
```


### Retourwaarde

Een [IThemeEffectiveData](../../ithemeeffectivedata/).
## Opmerkingen



Dit voorbeeld toont het ophalen van effectieve thema-eigenschappen. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveTheme = pres->get_Slides()->idx_get(0)->get_ThemeManager()->get_OverrideTheme()->GetEffective();

Console::WriteLine(String(u"Font scheme name: ") + effectiveTheme->get_FontScheme()->get_Name());
Console::WriteLine(String(u"Major latin font: ") + effectiveTheme->get_FontScheme()->get_Major()->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Minor latin font: ") + effectiveTheme->get_FontScheme()->get_Minor()->get_LatinFont()->get_FontName());
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IThemeEffectiveData](../../ithemeeffectivedata/)
* Klasse [Theme](../)
* Naamruimte [Aspose::Slides::Theme](../../)
* Bibliotheek [Aspose.Slides](../../../)