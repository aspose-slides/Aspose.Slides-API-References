---
title: GetEffective()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Pobiera efektywne dane motywu z zastosowanym dziedziczeniem.
type: docs
weight: 53
url: /pl/aspose.slides.theme/theme/geteffective/
---
## Theme::GetEffective() metoda


Pobiera efektywne dane motywu z zastosowanym dziedziczeniem.

```cpp
System::SharedPtr<IThemeEffectiveData> Aspose::Slides::Theme::Theme::GetEffective() override
```


### Wartość zwracana

Obiekt [IThemeEffectiveData](../../ithemeeffectivedata/).
## Uwagi



Ten przykład demonstruje pobieranie efektywnych właściwości motywu.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveTheme = pres->get_Slides()->idx_get(0)->get_ThemeManager()->get_OverrideTheme()->GetEffective();

Console::WriteLine(String(u"Font scheme name: ") + effectiveTheme->get_FontScheme()->get_Name());
Console::WriteLine(String(u"Major latin font: ") + effectiveTheme->get_FontScheme()->get_Major()->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Minor latin font: ") + effectiveTheme->get_FontScheme()->get_Minor()->get_LatinFont()->get_FontName());
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IThemeEffectiveData](../../ithemeeffectivedata/)
* Klasa [Theme](../)
* Przestrzeń nazw [Aspose::Slides::Theme](../../)
* Biblioteka [Aspose.Slides](../../../)