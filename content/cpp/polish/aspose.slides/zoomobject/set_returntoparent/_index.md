---
title: set_ReturnToParent()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Ustawia zachowanie nawigacji w pokazie slajdów. Zapisz bool. Wartość domyślna: false"
type: docs
weight: 40
url: /pl/aspose.slides/zoomobject/set_returntoparent/
---
## ZoomObject::set_ReturnToParent(bool) metoda


Ustawia zachowanie nawigacji w pokazie slajdów. Zapisz **bool**. Wartość domyślna: false

```cpp
void Aspose::Slides::ZoomObject::set_ReturnToParent(bool value) override
```

## Uwagi


Prawdziwa wartość własności określa zachowanie powrotu do elementu nadrzędnego w pokazie slajdów. 

Przykład: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Zobacz także

* Klasa [ZoomObject](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)