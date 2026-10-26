---
title: get_Layout()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Pobiera układ sekcji Summary Zoom w ramce. Wartość domyślna to GridLayout.
type: docs
weight: 1
url: /pl/aspose.slides/summaryzoomframe/get_layout/
---
## metoda SummaryZoomFrame::get_Layout()

Pobiera układ sekcji Summary Zoom w ramce. Wartość domyślna to GridLayout.

```cpp
ZoomLayout Aspose::Slides::SummaryZoomFrame::get_Layout() override
```

## Uwagi

Przykład demonstruje pobieranie elementu Summary Zoom [Section](../../section/) po indeksie: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Zobacz także

* Enum [ZoomLayout](../../zoomlayout/)
* Klasa [SummaryZoomFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)