---
title: get_ReturnToParent()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Pobiera zachowanie nawigacji w pokazie slajdów. Odczyt bool. Wartość domyślna: false"
type: docs
weight: 27
url: /pl/aspose.slides/izoomobject/get_returntoparent/
---
## IZoomObject::get_ReturnToParent() metoda


Pobiera zachowanie nawigacji w pokazie slajdów. Odczyt **bool**. Wartość domyślna: false

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ReturnToParent()=0
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