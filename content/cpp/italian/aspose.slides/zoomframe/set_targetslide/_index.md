---
title: set_TargetSlide()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta l'oggetto diapositiva a cui è collegato l'oggetto Slide Zoom. Scrivi ISlide.
type: docs
weight: 14
url: /it/aspose.slides/zoomframe/set_targetslide/
---
## ZoomFrame::set_TargetSlide(System::SharedPtr\<ISlide\>) metodo


Imposta l'oggetto diapositiva a cui il oggetto [Slide](../../slide/) Zoom è collegato. Scrivi [ISlide](../../islide/).

```cpp
void Aspose::Slides::ZoomFrame::set_TargetSlide(System::SharedPtr<ISlide> value) override
```

## Osservazioni


Il prossimo esempio dimostra la modifica della diapositiva di destinazione e crea una nuova immagine per l'oggetto [Slide](../../slide/) Zoom: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TargetSlide(pres->get_Slides()->idx_get(2));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [ZoomFrame](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)