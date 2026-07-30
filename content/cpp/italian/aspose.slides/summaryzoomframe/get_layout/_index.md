---
title: get_Layout()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce il layout delle sezioni Summary Zoom nel frame. Il valore predefinito è GridLayout.
type: docs
weight: 1
url: /it/aspose.slides/summaryzoomframe/get_layout/
---
## SummaryZoomFrame::get_Layout() metodo

Restituisce il layout delle sezioni Summary Zoom nel frame. Il valore predefinito è GridLayout.

```cpp
ZoomLayout Aspose::Slides::SummaryZoomFrame::get_Layout() override
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
* Classe [SummaryZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)