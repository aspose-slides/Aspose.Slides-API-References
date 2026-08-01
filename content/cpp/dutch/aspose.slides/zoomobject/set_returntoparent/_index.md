---
title: set_ReturnToParent()
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt het navigatiegedrag in de diavoorstelling in. Schrijf bool. Standaardwaarde: false"
type: docs
weight: 40
url: /nl/aspose.slides/zoomobject/set_returntoparent/
---
## ZoomObject::set_ReturnToParent(bool) methode


Stelt het navigatiegedrag in de diavoorstelling in. Schrijf **bool**. Standaardwaarde: false

```cpp
void Aspose::Slides::ZoomObject::set_ReturnToParent(bool value) override
```

## Opmerkingen


De true-waarde van de eigenschap specificeert het terugkeer-naar-ouder navigatiegedrag in de diavoorstelling. 

Voorbeeld: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Zie ook

* Klasse [ZoomObject](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)