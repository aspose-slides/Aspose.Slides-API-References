---
title: get_Layout()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o layout das seções de Summary Zoom no quadro. O valor padrão é GridLayout.
type: docs
weight: 1
url: /pt/aspose.slides/summaryzoomframe/get_layout/
---
## SummaryZoomFrame::get_Layout() método

Obtém o layout das seções de Sumário de Zoom no quadro. O valor padrão é GridLayout.

```cpp
ZoomLayout Aspose::Slides::SummaryZoomFrame::get_Layout() override
```

## Observações

O exemplo demonstra como obter o elemento Summary Zoom [Section](../../section/) por índice: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Ver também

* Enum [ZoomLayout](../../zoomlayout/)
* Classe [SummaryZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)