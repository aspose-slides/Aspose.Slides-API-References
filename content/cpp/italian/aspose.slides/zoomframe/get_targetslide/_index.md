---
title: get_TargetSlide()
second_title: Riferimento API Aspose.Slides per C++
description: Ottiene l'oggetto slide a cui l'oggetto Slide Zoom è collegato. Leggi ISlide.
type: docs
weight: 1
url: /it/aspose.slides/zoomframe/get_targetslide/
---
## ZoomFrame::get_TargetSlide() metodo

Ottiene l'oggetto slide a cui l'oggetto [Slide](../../slide/) Zoom è collegato. Leggi [ISlide](../../islide/).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::ZoomFrame::get_TargetSlide() override
```

## Note

Il prossimo esempio dimostra come modificare la slide di destinazione e crea una nuova immagine per l'oggetto [Slide](../../slide/) Zoom:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [ZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)