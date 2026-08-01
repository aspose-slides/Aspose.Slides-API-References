---
title: get_ReturnToParent()
second_title: Aspose.Slides voor C++ API-referentie
description: "Haalt het navigatiegedrag in diavoorstelling op. Lezen bool. Standaardwaarde: false"
type: docs
weight: 27
url: /nl/aspose.slides/izoomobject/get_returntoparent/
---
## IZoomObject::get_ReturnToParent() methode

Haalt het navigatiegedrag in diavoorstelling op. Lezen **bool**. Standaardwaarde: false

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ReturnToParent()=0
```

## Opmerkingen

Een waar-waarde van de eigenschap specificeert het terugkeren-naar-ouder navigatiegedrag in diavoorstelling.

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