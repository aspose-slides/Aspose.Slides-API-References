---
title: get_ShowBackground()
second_title: Aspose.Slides dla C++ – referencja API
description: "Pobiera wartość określającą, czy Zoom użyje tła docelowego slajdu. Odczyt bool. Wartość domyślna: true"
type: docs
weight: 53
url: /pl/aspose.slides/izoomobject/get_showbackground/
---
## IZoomObject::get_ShowBackground() metoda

Pobiera wartość określającą, czy Zoom użyje tła docelowego slajdu. Odczyt **bool**. Wartość domyślna: true

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ShowBackground()=0
```

## Uwagi

Przykład demonstruje usunięcie tła obrazu obiektu Zoom:
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