---
title: get_Layout()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt das Layout der Summary-Zoom-Abschnitte im Frame. Der Standardwert ist GridLayout.
type: docs
weight: 1
url: /de/aspose.slides/isummaryzoomframe/get_layout/
---
## ISummaryZoomFrame::get_Layout() Methode


Ermittelt das Layout der Summary-Zoom-Abschnitte im Frame. Der Standardwert ist GridLayout.

```cpp
virtual ZoomLayout Aspose::Slides::ISummaryZoomFrame::get_Layout()=0
```

## Hinweise


Das Beispiel zeigt das Abrufen des Summary-Zoom-[Section](../../section/)-Elements nach Index: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Siehe auch

* Enum [ZoomLayout](../../zoomlayout/)
* Class [ISummaryZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)