---
title: set_ShowBackground()
second_title: Riferimento API di Aspose.Slides per C++
description: "Imposta il valore che specifica se lo Zoom utilizzerà lo sfondo della diapositiva di destinazione. Scrivi bool. Valore predefinito: true"
type: docs
weight: 66
url: /it/aspose.slides/zoomobject/set_showbackground/
---
## ZoomObject::set_ShowBackground(bool) metodo

Imposta il valore che specifica se lo Zoom utilizzerà lo sfondo della diapositiva di destinazione. Scrivi **bool**. Valore predefinito: true

```cpp
void Aspose::Slides::ZoomObject::set_ShowBackground(bool value) override
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
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)