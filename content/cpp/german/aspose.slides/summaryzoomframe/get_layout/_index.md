---
title: get_Layout()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt das Layout der Summary Zoom Sections im Frame. Der Standardwert ist GridLayout.
type: docs
weight: 1
url: /de/aspose.slides/summaryzoomframe/get_layout/
---
## SummaryZoomFrame::get_Layout() Methode

Ermittelt das Layout der Summary Zoom Sections im Frame. Der Standardwert ist GridLayout.

```cpp
ZoomLayout Aspose::Slides::SummaryZoomFrame::get_Layout() override
```

## Anmerkungen

Das Beispiel zeigt, wie das Summary Zoom [Section](../../section/) Element nach Index abgerufen wird:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Siehe auch

* Enum [ZoomLayout](../../zoomlayout/)
* Klasse [SummaryZoomFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)