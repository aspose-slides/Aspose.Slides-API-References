---
title: get_ShowBackground()
second_title: Riferimento API Aspose.Slides per C++
description: "Restituisce il valore che specifica se lo Zoom utilizzerà lo sfondo della diapositiva di destinazione. Leggi bool. Valore predefinito: true"
type: docs
weight: 53
url: /it/aspose.slides/zoomobject/get_showbackground/
---
## ZoomObject::get_ShowBackground() metodo


Restituisce il valore che specifica se lo Zoom utilizzerà lo sfondo della diapositiva di destinazione. Leggi **bool**. Valore predefinito: true

```cpp
bool Aspose::Slides::ZoomObject::get_ShowBackground() override
```

## Osservazioni


l'esempio dimostra la rimozione dello sfondo di un'immagine di un oggetto Zoom: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Vedi anche

* Classe [ZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)