---
title: set_TargetSection()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt het sectieobject in waarnaar het Section Zoom-object linkt. Schrijf ISection.
type: docs
weight: 14
url: /nl/aspose.slides/sectionzoomframe/set_targetsection/
---
## SectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) methode

Stelt het sectie-object in waarnaar het [Section](../../section/) Zoom-object linkt. Schrijf [ISection](../../isection/).

```cpp
void Aspose::Slides::SectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value) override
```

## Opmerkingen

Het volgende voorbeeld toont het wijzigen van de doel-sectie en maakt een nieuw beeld voor het sectie-zoom-object:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISection](../../isection/)
* Klasse [SectionZoomFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)