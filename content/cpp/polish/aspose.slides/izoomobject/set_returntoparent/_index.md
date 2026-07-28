---
title: set_ReturnToParent()
second_title: Aspose.Slides dla C++ - odniesienie API
description: "Ustawia zachowanie nawigacji w pokazie slajdów. Zapisz bool. Domyślna wartość: false"
type: docs
weight: 40
url: /pl/aspose.slides/izoomobject/set_returntoparent/
---
## IZoomObject::set_ReturnToParent(bool) metoda


Ustawia zachowanie nawigacji w pokazie slajdów. Zapisz **bool**. Domyślna wartość: false

```cpp
virtual void Aspose::Slides::IZoomObject::set_ReturnToParent(bool value)=0
```

## Uwagi


Prawdziwa wartość właściwości określa zachowanie nawigacji powrotu do rodzica w pokazie slajdów. 

Przykład: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Zobacz także

* Klasa [IZoomObject](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)