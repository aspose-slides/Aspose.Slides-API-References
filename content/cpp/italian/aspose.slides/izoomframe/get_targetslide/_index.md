---
title: get_TargetSlide()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce l'oggetto slide a cui l'oggetto Slide Zoom è collegato. Leggi ISlide.
type: docs
weight: 1
url: /it/aspose.slides/izoomframe/get_targetslide/
---
## IZoomFrame::get_TargetSlide() metodo

Restituisce l'oggetto slide a cui il [Slide](../../slide/) oggetto Zoom è collegato. Leggi [ISlide](../../islide/).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::IZoomFrame::get_TargetSlide()=0
```

## Osservazioni

Il prossimo esempio dimostra come modificare la slide di destinazione e crea una nuova immagine per il [Slide](../../slide/) oggetto Zoom:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [IZoomFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)