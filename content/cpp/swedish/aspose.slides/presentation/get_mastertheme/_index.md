---
title: get_MasterTheme()
second_title: Aspose.Slides för C++ API-referens
description: "Returnerar huvudtema. Endast läsning Theme::IMasterTheme."
type: docs
weight: 404
url: /sv/aspose.slides/presentation/get_mastertheme/
---
## Presentation::get_MasterTheme() metod


Returnerar huvudtema. Endast läsning [Theme::IMasterTheme](../../../aspose.slides.theme/imastertheme/).

```cpp
System::SharedPtr<Theme::IMasterTheme> Aspose::Slides::Presentation::get_MasterTheme() override
```

## Anmärkningar


Följande exempel visar hur man ändrar en temaeffekt genom att förändra delar av element i PowerPoint [Presentation](../).
```cpp
// Skapa ett presentationsobjekt som representerar en presentationsfil
auto pres = System::MakeObject<Presentation>(u"Subtle_Moderate_Intense.pptx");
auto masterTheme = pres->get_MasterTheme();
auto formatScheme = masterTheme->get_FormatScheme();

formatScheme->get_LineStyles()->idx_get(0)->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
formatScheme->get_FillStyles()->idx_get(2)->set_FillType(FillType::Solid);
formatScheme->get_FillStyles()->idx_get(2)->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
formatScheme->get_EffectStyles()->idx_get(2)->get_EffectFormat()->get_OuterShadowEffect()->set_Distance(10.0f);
pres->Save(u"Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat::Pptx);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMasterTheme](../../../aspose.slides.theme/imastertheme/)
* Klass [Presentation](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)