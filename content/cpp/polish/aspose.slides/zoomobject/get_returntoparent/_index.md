---
title: get_ReturnToParent()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Pobiera zachowanie nawigacji w pokazie slajdów. Odczyt bool. Domyślna wartość: false"
type: docs
weight: 27
url: /pl/aspose.slides/zoomobject/get_returntoparent/
---
## ZoomObject::get_ReturnToParent() metoda


Pobiera zachowanie nawigacji w pokazie slajdów. Odczyt **bool**. Domyślna wartość: false

```cpp
bool Aspose::Slides::ZoomObject::get_ReturnToParent() override
```

## Uwagi


Prawdziwa wartość właściwości określa zachowanie nawigacji powrotu do elementu nadrzędnego w pokazie slajdów. 

Przykład: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Zobacz także

* Klasa [ZoomObject](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)