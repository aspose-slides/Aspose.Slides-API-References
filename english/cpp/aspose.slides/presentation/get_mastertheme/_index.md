---
title: get_MasterTheme()
second_title: Aspose.Slides for C++ API Reference
description: "Returns master theme. Read-only Theme::IMasterTheme."
type: docs
weight: 391
url: /cpp/aspose.slides/presentation/get_mastertheme/
---
## Presentation::get_MasterTheme() method


Returns master theme. Read-only [Theme::IMasterTheme](../../../aspose.slides.theme/imastertheme/).

```cpp
System::SharedPtr<Theme::IMasterTheme> Aspose::Slides::Presentation::get_MasterTheme() override
```

## Remarks


The following examples shows how to change a theme effect by altering parts of elements of PowerPoint [Presentation](../). 
```cpp
// Instantiate a presentation object that represents a presentation file
auto pres = System::MakeObject<Presentation>(u"Subtle_Moderate_Intense.pptx");
auto masterTheme = pres->get_MasterTheme();
auto formatScheme = masterTheme->get_FormatScheme();

formatScheme->get_LineStyles()->idx_get(0)->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
formatScheme->get_FillStyles()->idx_get(2)->set_FillType(FillType::Solid);
formatScheme->get_FillStyles()->idx_get(2)->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
formatScheme->get_EffectStyles()->idx_get(2)->get_EffectFormat()->get_OuterShadowEffect()->set_Distance(10.0f);
pres->Save(u"Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMasterTheme](../../../aspose.slides.theme/imastertheme/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)