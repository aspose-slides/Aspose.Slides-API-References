---
title: set_ReturnToParent()
second_title: Riferimento API di Aspose.Slides per C++
description: "Imposta il comportamento di navigazione nella presentazione. Scrivi bool. Valore predefinito: false"
type: docs
weight: 40
url: /it/aspose.slides/zoomobject/set_returntoparent/
---
## ZoomObject::set_ReturnToParent(bool) metodo


Imposta il comportamento di navigazione nella presentazione. Scrivi **bool**. Valore predefinito: false

```cpp
void Aspose::Slides::ZoomObject::set_ReturnToParent(bool value) override
```

## Osservazioni


Il valore true della proprietà specifica il comportamento di ritorno al padre nella presentazione. 

Esempio: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Vedi anche

* Classe [ZoomObject](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)