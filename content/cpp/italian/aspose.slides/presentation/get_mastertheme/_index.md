---
title: get_MasterTheme()
second_title: Riferimento API Aspose.Slides per C++
description: "Restituisce il tema master. Solo lettura Theme::IMasterTheme."
type: docs
weight: 404
url: /it/aspose.slides/presentation/get_mastertheme/
---
## Presentation::get_MasterTheme() metodo

Restituisce il tema master. Solo lettura [Theme::IMasterTheme](../../../aspose.slides.theme/imastertheme/).

```cpp
System::SharedPtr<Theme::IMasterTheme> Aspose::Slides::Presentation::get_MasterTheme() override
```

## Osservazioni

Gli esempi seguenti mostrano come modificare un effetto del tema alterando parti degli elementi di PowerPoint [Presentation](../). 
```cpp
// Istanzia un oggetto Presentation che rappresenta un file di presentazione
auto pres = System::MakeObject<Presentation>(u"Subtle_Moderate_Intense.pptx");
auto masterTheme = pres->get_MasterTheme();
auto formatScheme = masterTheme->get_FormatScheme();

formatScheme->get_LineStyles()->idx_get(0)->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
formatScheme->get_FillStyles()->idx_get(2)->set_FillType(FillType::Solid);
formatScheme->get_FillStyles()->idx_get(2)->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
formatScheme->get_EffectStyles()->idx_get(2)->get_EffectFormat()->get_OuterShadowEffect()->set_Distance(10.0f);
pres->Save(u"Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMasterTheme](../../../aspose.slides.theme/imastertheme/)
* Classe [Presentation](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)