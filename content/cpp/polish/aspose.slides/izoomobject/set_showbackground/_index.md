---
title: set_ShowBackground()
second_title: Aspose.Slides dla C++ odniesienie API
description: "Ustawia wartość określającą, czy Zoom będzie używać tła docelowego slajdu. Zapisz bool. Domyślna wartość: true"
type: docs
weight: 66
url: /pl/aspose.slides/izoomobject/set_showbackground/
---
## IZoomObject::set_ShowBackground(bool) metoda

Ustawia wartość określającą, czy Zoom użyje tła slajdu docelowego. Zapisz **bool**. Domyślna wartość: true

```cpp
virtual void Aspose::Slides::IZoomObject::set_ShowBackground(bool value)=0
```

## Uwagi

Przykład demonstruje usuwanie tła obrazu obiektu Zoom: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Zobacz także

* Klasa [IZoomObject](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)