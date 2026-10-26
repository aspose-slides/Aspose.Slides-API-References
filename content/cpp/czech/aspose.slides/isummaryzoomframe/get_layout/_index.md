---
title: get_Layout()
second_title: Aspose.Slides pro C++ API Reference
description: Získá rozložení sekcí Summary Zoom ve snímku. Výchozí hodnota je GridLayout.
type: docs
weight: 1
url: /cs/aspose.slides/isummaryzoomframe/get_layout/
---
## ISummaryZoomFrame::get_Layout() method

Získá rozložení sekcí Summary Zoom ve snímku. Výchozí hodnota je GridLayout.

```cpp
virtual ZoomLayout Aspose::Slides::ISummaryZoomFrame::get_Layout()=0
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

* Výčet [ZoomLayout](../../zoomlayout/)
* Třída [ISummaryZoomFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)