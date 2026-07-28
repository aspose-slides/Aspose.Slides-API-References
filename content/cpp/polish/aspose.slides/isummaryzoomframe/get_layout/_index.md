---
title: get_Layout()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Pobiera układ sekcji Summary Zoom w ramce. Domyślna wartość to GridLayout.
type: docs
weight: 1
url: /pl/aspose.slides/isummaryzoomframe/get_layout/
---
## ISummaryZoomFrame::get_Layout() metoda

Pobiera układ sekcji Summary Zoom w ramce. Domyślna wartość to GridLayout.

```cpp
virtual ZoomLayout Aspose::Slides::ISummaryZoomFrame::get_Layout()=0
```

## Uwagi

Przykład demonstruje pobieranie elementu Summary Zoom [Section](../../section/) według indeksu:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Zobacz także

* Enum [ZoomLayout](../../zoomlayout/)
* Klasa [ISummaryZoomFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)