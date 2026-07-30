---
title: get_TransitionDuration()
second_title: Riferimento API Aspose.Slides per C++
description: "Restituisce la durata della transizione tra Zoom e diapositiva. Leggi float. Valore predefinito: 1.0f"
type: docs
weight: 105
url: /it/aspose.slides/izoomobject/get_transitionduration/
---
## IZoomObject::get_TransitionDuration() metodo

Restituisce la durata della transizione tra Zoom e diapositiva. Leggi **float**. Valore predefinito: 1.0f

```cpp
virtual float Aspose::Slides::IZoomObject::get_TransitionDuration()=0
```

## Osservazioni

Se non specificato (TransitionDur = 0), verrà utilizzata la transizione della diapositiva di destinazione e i tempi associati a quella transizione. 

l'esempio dimostra come modificare la durata della transizione tra Zoom e diapositiva: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_TransitionDuration(2.5f);
```

## Vedi anche

* Classe [IZoomObject](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)