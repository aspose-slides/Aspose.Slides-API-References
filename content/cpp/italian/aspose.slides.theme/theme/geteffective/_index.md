---
title: GetEffective()
second_title: Aspose.Slides per C++ Riferimento API
description: Ottiene i dati del tema effettivo con l'ereditarietà applicata.
type: docs
weight: 53
url: /it/aspose.slides.theme/theme/geteffective/
---
## Theme::GetEffective() metodo

Ottiene i dati del tema efficaci con l'ereditarietà applicata.

```cpp
System::SharedPtr<IThemeEffectiveData> Aspose::Slides::Theme::Theme::GetEffective() override
```

### Valore di ritorno

Un [IThemeEffectiveData](../../ithemeeffectivedata/).
## Osservazioni

Questo esempio dimostra come ottenere le proprietà del tema efficaci. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveTheme = pres->get_Slides()->idx_get(0)->get_ThemeManager()->get_OverrideTheme()->GetEffective();

Console::WriteLine(String(u"Font scheme name: ") + effectiveTheme->get_FontScheme()->get_Name());
Console::WriteLine(String(u"Major latin font: ") + effectiveTheme->get_FontScheme()->get_Major()->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Minor latin font: ") + effectiveTheme->get_FontScheme()->get_Minor()->get_LatinFont()->get_FontName());
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IThemeEffectiveData](../../ithemeeffectivedata/)
* Classe [Theme](../)
* Spazio dei nomi [Aspose::Slides::Theme](../../)
* Libreria [Aspose.Slides](../../../)