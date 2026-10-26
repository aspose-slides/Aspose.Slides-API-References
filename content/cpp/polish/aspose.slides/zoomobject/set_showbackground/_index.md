---
title: set_ShowBackground()
second_title: Aspose.Slides dla C++ - odniesienie API
description: "Ustawia wartość określającą, czy Zoom użyje tła slajdu docelowego. Zapisz bool. Domyślna wartość: true"
type: docs
weight: 66
url: /pl/aspose.slides/zoomobject/set_showbackground/
---
## ZoomObject::set_ShowBackground(bool) metoda


Ustawia wartość określającą, czy Zoom użyje tła slajdu docelowego. Zapisz **bool**. Domyślna wartość: true

```cpp
void Aspose::Slides::ZoomObject::set_ShowBackground(bool value) override
```

## Uwagi


przykład demonstruje usuwanie tła obrazu obiektu Zoom: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Zobacz także

* Klasa [ZoomObject](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)