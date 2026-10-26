---
title: get_Layout()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene il layout delle sezioni Summary Zoom nel frame. Il valore predefinito è GridLayout.
type: docs
weight: 1
url: /it/aspose.slides/isummaryzoomframe/get_layout/
---
## ISummaryZoomFrame::get_Layout() metodo

Ottiene il layout delle sezioni Summary Zoom nel frame. Il valore predefinito è GridLayout.

```cpp
virtual ZoomLayout Aspose::Slides::ISummaryZoomFrame::get_Layout()=0
```

## Osservazioni

L'esempio dimostra come ottenere l'elemento Summary Zoom [Section](../../section/) per indice:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Vedi anche

* Enum [ZoomLayout](../../zoomlayout/)
* Class [ISummaryZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)