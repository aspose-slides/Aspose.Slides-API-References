---
title: set_TargetSection()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt het sectieobject in waarmee het Section Zoom-object is gekoppeld. Schrijf ISection.
type: docs
weight: 14
url: /nl/aspose.slides/isectionzoomframe/set_targetsection/
---
## ISectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) methode


Stelt het sectieobject in waarmee het [Section](../../section/) Zoom-object is gekoppeld. Schrijf [ISection](../../isection/).

```cpp
virtual void Aspose::Slides::ISectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value)=0
```

## Opmerkingen


Dit voorbeeld demonstreert het wijzigen van de doelsectie en maakt een nieuwe afbeelding voor het sectiezoomobject: 
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
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)