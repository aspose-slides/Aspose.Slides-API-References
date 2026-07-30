---
title: get_ShowBackground()
second_title: Riferimento API di Aspose.Slides per C++
description: "Restituisce il valore che specifica se lo Zoom utilizzerà lo sfondo della diapositiva di destinazione. Leggi bool. Valore predefinito: true"
type: docs
weight: 53
url: /it/aspose.slides/izoomobject/get_showbackground/
---
## IZoomObject::get_ShowBackground() metodo

Ottiene il valore che specifica se lo Zoom utilizzerà lo sfondo della diapositiva di destinazione. Leggi **bool**. Valore predefinito: true

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ShowBackground()=0
```

## Osservazioni

L'esempio dimostra come rimuovere lo sfondo di un'immagine di un oggetto Zoom: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Vedi anche

* Classe [IZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)