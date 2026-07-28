---
title: get_MasterTheme()
second_title: Aspose.Slides C++ API-referencia
description: "Visszaadja a fő témát. Csak olvasható Theme::IMasterTheme."
type: docs
weight: 404
url: /hu/aspose.slides/presentation/get_mastertheme/
---
## Presentation::get_MasterTheme() metódus


A fő témát adja vissza. Csak olvasható [Theme::IMasterTheme](../../../aspose.slides.theme/imastertheme/).

```cpp
System::SharedPtr<Theme::IMasterTheme> Aspose::Slides::Presentation::get_MasterTheme() override
```

## Megjegyzések


A következő példák bemutatják, hogyan változtatható a téma hatása a PowerPoint elemeinek részeinek módosításával [Presentation](../).
```cpp
// Példányosít egy prezentáció objektumot, amely egy prezentációs fájlt képvisel
auto pres = System::MakeObject<Presentation>(u"Subtle_Moderate_Intense.pptx");
auto masterTheme = pres->get_MasterTheme();
auto formatScheme = masterTheme->get_FormatScheme();

formatScheme->get_LineStyles()->idx_get(0)->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
formatScheme->get_FillStyles()->idx_get(2)->set_FillType(FillType::Solid);
formatScheme->get_FillStyles()->idx_get(2)->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
formatScheme->get_EffectStyles()->idx_get(2)->get_EffectFormat()->get_OuterShadowEffect()->set_Distance(10.0f);
pres->Save(u"Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMasterTheme](../../../aspose.slides.theme/imastertheme/)
* Osztály [Presentation](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)