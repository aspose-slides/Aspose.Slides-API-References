---
title: set_TargetSlide()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt das Folienobjekt, auf das das Slide Zoom-Objekt verlinkt. Schreiben Sie ISlide.
type: docs
weight: 14
url: /de/aspose.slides/izoomframe/set_targetslide/
---
## IZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) Methode

Setzt das Folienobjekt, auf das das [Slide](../../slide/) Zoom-Objekt verlinkt. Schreiben Sie [ISlide](../../islide/).

```cpp
virtual void Aspose::Slides::IZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value)=0
```

## Bemerkungen

Das folgende Beispiel demonstriert das Ändern der Zielfolie und erstellt ein neues Bild für das [Slide](../../slide/) Zoom-Objekt: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlide](../../islide/)
* Klasse [IZoomFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)