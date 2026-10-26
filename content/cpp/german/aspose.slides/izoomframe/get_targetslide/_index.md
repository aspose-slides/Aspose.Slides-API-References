---
title: get_TargetSlide()
second_title: Aspose.Slides für C++ API Referenz
description: Ruft das Folienobjekt ab, auf das das Slide Zoom-Objekt verweist. Lesen Sie ISlide.
type: docs
weight: 1
url: /de/aspose.slides/izoomframe/get_targetslide/
---
## IZoomFrame::get_TargetSlide() Methode


Ruft das Folienobjekt ab, auf das das [Slide](../../slide/) Zoom-Objekt verweist. Lesen Sie [ISlide](../../islide/).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::IZoomFrame::get_TargetSlide()=0
```

## Anmerkungen


Das nächste Beispiel demonstriert das Ändern der Zielfolie und erstellt ein neues Bild für das [Slide](../../slide/) Zoom-Objekt: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlide](../../islide/)
* Klasse [IZoomFrame](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)