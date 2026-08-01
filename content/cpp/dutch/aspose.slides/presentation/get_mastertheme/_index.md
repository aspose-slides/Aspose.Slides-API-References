---
title: get_MasterTheme()
second_title: Aspose.Slides voor C++ API-referentie
description: "Retourneert masterthema. Alleen-lezen Theme::IMasterTheme."
type: docs
weight: 404
url: /nl/aspose.slides/presentation/get_mastertheme/
---
## Presentation::get_MasterTheme() methode


Retourneert masterthema. Alleen-lezen [Theme::IMasterTheme](../../../aspose.slides.theme/imastertheme/).

```cpp
System::SharedPtr<Theme::IMasterTheme> Aspose::Slides::Presentation::get_MasterTheme() override
```

## Opmerkingen


De volgende voorbeelden laten zien hoe u een thema-effect wijzigt door delen van elementen van PowerPoint [Presentation](../) aan te passen. 
```cpp
// Instantieer een presentatieobject dat een presentatiebestand vertegenwoordigt
auto pres = System::MakeObject<Presentation>(u"Subtle_Moderate_Intense.pptx");
auto masterTheme = pres->get_MasterTheme();
auto formatScheme = masterTheme->get_FormatScheme();

formatScheme->get_LineStyles()->idx_get(0)->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
formatScheme->get_FillStyles()->idx_get(2)->set_FillType(FillType::Solid);
formatScheme->get_FillStyles()->idx_get(2)->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
formatScheme->get_EffectStyles()->idx_get(2)->get_EffectFormat()->get_OuterShadowEffect()->set_Distance(10.0f);
pres->Save(u"Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMasterTheme](../../../aspose.slides.theme/imastertheme/)
* Klasse [Presentation](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)