---
title: get_MasterTheme()
second_title: Aspose.Slides pour C++ Référence de l'API
description: "Renvoie le thème maître. Lecture seule Theme::IMasterTheme."
type: docs
weight: 404
url: /fr/aspose.slides/presentation/get_mastertheme/
---
## Presentation::get_MasterTheme() méthode


Renvoie le thème maître. Lecture seule [Theme::IMasterTheme](../../../aspose.slides.theme/imastertheme/).

```cpp
System::SharedPtr<Theme::IMasterTheme> Aspose::Slides::Presentation::get_MasterTheme() override
```

## Remarques


Les exemples suivants montrent comment modifier un effet de thème en modifiant des parties des éléments de PowerPoint [Presentation](../). 
```cpp
// Instancier un objet Presentation qui représente un fichier de présentation
auto pres = System::MakeObject<Presentation>(u"Subtle_Moderate_Intense.pptx");
auto masterTheme = pres->get_MasterTheme();
auto formatScheme = masterTheme->get_FormatScheme();

formatScheme->get_LineStyles()->idx_get(0)->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
formatScheme->get_FillStyles()->idx_get(2)->set_FillType(FillType::Solid);
formatScheme->get_FillStyles()->idx_get(2)->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
formatScheme->get_EffectStyles()->idx_get(2)->get_EffectFormat()->get_OuterShadowEffect()->set_Distance(10.0f);
pres->Save(u"Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMasterTheme](../../../aspose.slides.theme/imastertheme/)
* Classe [Presentation](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)