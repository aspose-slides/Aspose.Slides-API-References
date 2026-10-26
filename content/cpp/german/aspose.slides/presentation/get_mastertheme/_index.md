---
title: get_MasterTheme()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt das Master-Theme zurück. Nur lesbar Theme::IMasterTheme."
type: docs
weight: 404
url: /de/aspose.slides/presentation/get_mastertheme/
---
## Presentation::get_MasterTheme() Methode


Gibt das Master-Theme zurück. Nur lesbar [Theme::IMasterTheme](../../../aspose.slides.theme/imastertheme/).

```cpp
System::SharedPtr<Theme::IMasterTheme> Aspose::Slides::Presentation::get_MasterTheme() override
```

## Hinweise


Die folgenden Beispiele zeigen, wie man einen Theme-Effekt ändert, indem man Teile von Elementen von PowerPoint [Presentation](../) verändert. 
```cpp
// Instanziiere ein Präsentationsobjekt, das eine Präsentationsdatei darstellt
auto pres = System::MakeObject<Presentation>(u"Subtle_Moderate_Intense.pptx");
auto masterTheme = pres->get_MasterTheme();
auto formatScheme = masterTheme->get_FormatScheme();

formatScheme->get_LineStyles()->idx_get(0)->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
formatScheme->get_FillStyles()->idx_get(2)->set_FillType(FillType::Solid);
formatScheme->get_FillStyles()->idx_get(2)->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
formatScheme->get_EffectStyles()->idx_get(2)->get_EffectFormat()->get_OuterShadowEffect()->set_Distance(10.0f);
pres->Save(u"Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMasterTheme](../../../aspose.slides.theme/imastertheme/)
* Klasse [Presentation](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)