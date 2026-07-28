---
title: get_ShowBackground()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Pobiera wartość określającą, czy Zoom użyje tła docelowego slajdu. Odczyt bool. Domyślna wartość: true"
type: docs
weight: 53
url: /pl/aspose.slides/zoomobject/get_showbackground/
---
## ZoomObject::get_ShowBackground() metoda


Pobiera wartość określającą, czy Zoom użyje tła docelowego slajdu. Odczyt **bool**. Domyślna wartość: true

```cpp
bool Aspose::Slides::ZoomObject::get_ShowBackground() override
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

* Klasa [ZoomObject](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)