---
title: GetEffective()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt wirksame Theme-Daten, wobei die Vererbung angewendet wird.
type: docs
weight: 53
url: /de/aspose.slides.theme/theme/geteffective/
---
## Theme::GetEffective() Methode

Ermittelt die wirksamen Theme-Daten, wobei die Vererbung angewendet wird.

```cpp
System::SharedPtr<IThemeEffectiveData> Aspose::Slides::Theme::Theme::GetEffective() override
```

### Rückgabewert

Ein [IThemeEffectiveData](../../ithemeeffectivedata/).
## Anmerkungen

Dieses Beispiel demonstriert das Abrufen wirksamer Theme-Eigenschaften. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveTheme = pres->get_Slides()->idx_get(0)->get_ThemeManager()->get_OverrideTheme()->GetEffective();

Console::WriteLine(String(u"Font scheme name: ") + effectiveTheme->get_FontScheme()->get_Name());
Console::WriteLine(String(u"Major latin font: ") + effectiveTheme->get_FontScheme()->get_Major()->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Minor latin font: ") + effectiveTheme->get_FontScheme()->get_Minor()->get_LatinFont()->get_FontName());
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IThemeEffectiveData](../../ithemeeffectivedata/)
* Klasse [Theme](../)
* Namensraum [Aspose::Slides::Theme](../../)
* Bibliothek [Aspose.Slides](../../../)