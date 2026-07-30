---
title: set_ReturnToParent()
second_title: Aspose.Slides per C++ Riferimento API
description: "Imposta il comportamento di navigazione nella presentazione. Scrivi bool. Valore predefinito: false"
type: docs
weight: 40
url: /it/aspose.slides/izoomobject/set_returntoparent/
---
## IZoomObject::set_ReturnToParent(bool) metodo


Imposta il comportamento di navigazione nella presentazione. Scrivi **bool**. Valore predefinito: false

```cpp
virtual void Aspose::Slides::IZoomObject::set_ReturnToParent(bool value)=0
```

## Osservazioni


Il valore true della proprietà specifica il comportamento di ritorno al genitore nella presentazione. 

Esempio: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Vedi anche

* Classe [IZoomObject](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)