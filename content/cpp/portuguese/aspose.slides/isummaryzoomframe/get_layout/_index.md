---
title: get_Layout()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o layout das Seções de Zoom de Resumo no quadro. O valor padrão é GridLayout.
type: docs
weight: 1
url: /pt/aspose.slides/isummaryzoomframe/get_layout/
---
## ISummaryZoomFrame::get_Layout() método

Obtém o layout das Seções de Zoom de Resumo no quadro. O valor padrão é GridLayout.

```cpp
virtual ZoomLayout Aspose::Slides::ISummaryZoomFrame::get_Layout()=0
```

## Observações

O exemplo demonstra a obtenção do elemento Summary Zoom [Section](../../section/) por índice: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Ver também

* Enum [ZoomLayout](../../zoomlayout/)
* Classe [ISummaryZoomFrame](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)