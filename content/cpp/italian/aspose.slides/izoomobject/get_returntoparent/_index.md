---
title: get_ReturnToParent()
second_title: Riferimento API di Aspose.Slides per C++
description: "Ottiene il comportamento di navigazione nella presentazione. Legge bool. Valore predefinito: false"
type: docs
weight: 27
url: /it/aspose.slides/izoomobject/get_returntoparent/
---
## IZoomObject::get_ReturnToParent() metodo

Ottiene il comportamento di navigazione nella presentazione. Legge **bool**. Valore predefinito: false

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ReturnToParent()=0
```

## Osservazioni

Il valore vero della proprietà specifica il comportamento di ritorno al genitore nella presentazione. 

Esempio: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Vedi anche

* Classe [IZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)