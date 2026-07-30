---
title: get_Layout()
second_title: Aspose.Slides pro C++ API Reference
description: Získá rozvržení sekcí Summary Zoom ve snímku. Výchozí hodnota je GridLayout.
type: docs
weight: 1
url: /cs/aspose.slides/summaryzoomframe/get_layout/
---
## SummaryZoomFrame::get_Layout() metoda


Získá rozvržení sekcí Summary Zoom ve snímku. Výchozí hodnota je GridLayout.

```cpp
ZoomLayout Aspose::Slides::SummaryZoomFrame::get_Layout() override
```

## Poznámky


Příklad ukazuje získání elementu Summary Zoom [Section](../../section/) podle indexu: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Viz také

* Enum [ZoomLayout](../../zoomlayout/)
* Třída [SummaryZoomFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)