---
title: set_ReturnToParent()
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt het navigatiegedrag in de diavoorstelling in. Schrijf bool. Standaardwaarde: false"
type: docs
weight: 40
url: /nl/aspose.slides/izoomobject/set_returntoparent/
---
## IZoomObject::set_ReturnToParent(bool) methode


Stelt het navigatiegedrag in de diavoorstelling in. Schrijf **bool**. Standaardwaarde: false

```cpp
virtual void Aspose::Slides::IZoomObject::set_ReturnToParent(bool value)=0
```

## Opmerkingen


Een waar-waarde van de eigenschap specificeert het terugkeren naar de bovenliggende navigatiegedrag in de diavoorstelling. 

Voorbeeld: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Zie ook

* Klasse [IZoomObject](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)