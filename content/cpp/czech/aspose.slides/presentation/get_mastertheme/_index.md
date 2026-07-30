---
title: get_MasterTheme()
second_title: Aspose.Slides pro C++ API Reference
description: "Vrací hlavní téma. Pouze ke čtení Theme::IMasterTheme."
type: docs
weight: 404
url: /cs/aspose.slides/presentation/get_mastertheme/
---
## Presentation::get_MasterTheme() metoda


Vrací hlavní téma. Pouze ke čtení [Theme::IMasterTheme](../../../aspose.slides.theme/imastertheme/).

```cpp
System::SharedPtr<Theme::IMasterTheme> Aspose::Slides::Presentation::get_MasterTheme() override
```

## Poznámky


Následující příklady ukazují, jak změnit efekt motivu úpravou částí prvků PowerPoint [Presentation](../). 
```cpp
// Vytvořte objekt prezentace, který představuje soubor prezentace
auto pres = System::MakeObject<Presentation>(u"Subtle_Moderate_Intense.pptx");
auto masterTheme = pres->get_MasterTheme();
auto formatScheme = masterTheme->get_FormatScheme();

formatScheme->get_LineStyles()->idx_get(0)->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
formatScheme->get_FillStyles()->idx_get(2)->set_FillType(FillType::Solid);
formatScheme->get_FillStyles()->idx_get(2)->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
formatScheme->get_EffectStyles()->idx_get(2)->get_EffectFormat()->get_OuterShadowEffect()->set_Distance(10.0f);
pres->Save(u"Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMasterTheme](../../../aspose.slides.theme/imastertheme/)
* Třída [Presentation](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)