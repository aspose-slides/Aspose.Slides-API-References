---
title: get_MasterTheme()
second_title: Aspose.Slides dla C++ API Reference
description: "Zwraca główny motyw. Tylko do odczytu Theme::IMasterTheme."
type: docs
weight: 404
url: /pl/aspose.slides/presentation/get_mastertheme/
---
## Presentation::get_MasterTheme() metoda

Zwraca główny motyw. Tylko do odczytu [Theme::IMasterTheme](../../../aspose.slides.theme/imastertheme/).

```cpp
System::SharedPtr<Theme::IMasterTheme> Aspose::Slides::Presentation::get_MasterTheme() override
```

## Uwagi

Poniższe przykłady pokazują, jak zmienić efekt motywu, modyfikując części elementów PowerPoint [Presentation](../).

```cpp
// Utwórz obiekt prezentacji, który reprezentuje plik prezentacji
auto pres = System::MakeObject<Presentation>(u"Subtle_Moderate_Intense.pptx");
auto masterTheme = pres->get_MasterTheme();
auto formatScheme = masterTheme->get_FormatScheme();

formatScheme->get_LineStyles()->idx_get(0)->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
formatScheme->get_FillStyles()->idx_get(2)->set_FillType(FillType::Solid);
formatScheme->get_FillStyles()->idx_get(2)->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
formatScheme->get_EffectStyles()->idx_get(2)->get_EffectFormat()->get_OuterShadowEffect()->set_Distance(10.0f);
pres->Save(u"Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMasterTheme](../../../aspose.slides.theme/imastertheme/)
* Klasa [Presentation](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)