---
title: get_TargetSection()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt het sectie-object op waar het Section Zoom-object naar linkt. Lees ISection.
type: docs
weight: 1
url: /nl/aspose.slides/sectionzoomframe/get_targetsection/
---
## SectionZoomFrame::get_TargetSection() methode


Haalt het sectieobject op waar het [Section](../../section/) Zoom-object naar linkt. Lees [ISection](../../isection/).

```cpp
System::SharedPtr<ISection> Aspose::Slides::SectionZoomFrame::get_TargetSection() override
```

## Opmerkingen


Het volgende voorbeeld laat zien hoe de doel-sectie wordt gewijzigd en een nieuwe afbeelding voor het sectie-zoom-object wordt gemaakt: 
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
* Bibliotheek [Aspose.Slides](../../../)