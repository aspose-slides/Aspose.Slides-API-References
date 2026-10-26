---
title: get_ReturnToParent()
second_title: Riferimento API Aspose.Slides per C++
description: "Ottiene il comportamento di navigazione nella presentazione. Lettura bool. Valore predefinito: false"
type: docs
weight: 27
url: /it/aspose.slides/zoomobject/get_returntoparent/
---
## ZoomObject::get_ReturnToParent() metodo


Ottiene il comportamento di navigazione nella presentazione. Lettura **bool**. Valore predefinito: false

```cpp
bool Aspose::Slides::ZoomObject::get_ReturnToParent() override
```

## Osservazioni


Il valore true della proprietà specifica il comportamento di ritorno al genitore nella presentazione. 

Esempio: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Vedi anche

* Classe [ZoomObject](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)