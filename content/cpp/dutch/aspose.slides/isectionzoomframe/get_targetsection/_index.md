---
title: get_TargetSection()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt het sectieobject op dat gekoppeld is aan het Section Zoom-object. Lees ISection.
type: docs
weight: 1
url: /nl/aspose.slides/isectionzoomframe/get_targetsection/
---
## ISectionZoomFrame::get_TargetSection() methode

Haalt het sectie-object op dat gekoppeld is aan het [Section](../../section/) Zoom-object. Lees [ISection](../../isection/).

```cpp
virtual System::SharedPtr<ISection> Aspose::Slides::ISectionZoomFrame::get_TargetSection()=0
```

## Opmerkingen

Dit voorbeeld demonstreert het wijzigen van de doelsectie en maakt een nieuwe afbeelding voor het sectie-zoom-object:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISection](../../isection/)
* Klasse [ISectionZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)