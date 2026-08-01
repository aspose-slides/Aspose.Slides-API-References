---
title: set_TargetSlide()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt het dia-object in waarop het Slide Zoom-object linkt. Schrijf ISlide.
type: docs
weight: 14
url: /nl/aspose.slides/zoomframe/set_targetslide/
---
## ZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) methode

Stelt het dia-object in waarop het [Slide](../../slide/) Zoom-object linkt. Schrijf [ISlide](../../islide/).

```cpp
void Aspose::Slides::ZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value) override
```

## Opmerkingen

Het volgende voorbeeld laat zien hoe de doel-dia wordt gewijzigd en maakt een nieuw beeld voor het [Slide](../../slide/) Zoom-object:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlide](../../islide/)
* Klasse [ZoomFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)