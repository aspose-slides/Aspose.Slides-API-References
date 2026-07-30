---
title: set_TransitionDuration()
second_title: Riferimento API di Aspose.Slides per C++
description: "Imposta la durata della transizione tra Zoom e diapositiva. Scrivi float. Valore predefinito: 1.0f"
type: docs
weight: 118
url: /it/aspose.slides/zoomobject/set_transitionduration/
---
## ZoomObject::set_TransitionDuration(float) metodo


Imposta la durata della transizione tra Zoom e diapositiva. Scrivi **float**. Valore predefinito: 1.0f

```cpp
void Aspose::Slides::ZoomObject::set_TransitionDuration(float value) override
```

## Osservazioni


Se non specificato (TransitionDur = 0), verrà utilizzata la transizione della diapositiva di destinazione e i tempi associati a quella transizione. 

L'esempio dimostra come modificare la durata della transizione tra Zoom e diapositiva: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Vedi anche

* Classe [ZoomObject](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)