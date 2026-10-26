---
title: set_ShowBackground()
second_title: Riferimento API Aspose.Slides per C++
description: "Imposta il valore che specifica se lo Zoom utilizzerà lo sfondo della diapositiva di destinazione. Scrivi bool. Valore predefinito: true"
type: docs
weight: 66
url: /it/aspose.slides/izoomobject/set_showbackground/
---
## IZoomObject::set_ShowBackground(bool) metodo

Imposta il valore che specifica se lo Zoom utilizzerà lo sfondo della diapositiva di destinazione. Scrivere **bool**. Valore predefinito: true

```cpp
virtual void Aspose::Slides::IZoomObject::set_ShowBackground(bool value)=0
```

## Osservazioni

L'esempio dimostra la rimozione dello sfondo di un'immagine di un oggetto Zoom: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Vedi anche

* Classe [IZoomObject](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)