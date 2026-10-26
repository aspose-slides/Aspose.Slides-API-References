---
title: get_Layout()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene el diseño de Summary Zoom Sections en el marco. El valor predeterminado es GridLayout.
type: docs
weight: 1
url: /es/aspose.slides/isummaryzoomframe/get_layout/
---
## ISummaryZoomFrame::get_Layout() método


Obtiene el diseño de Summary Zoom Sections en el marco. El valor predeterminado es GridLayout.

```cpp
virtual ZoomLayout Aspose::Slides::ISummaryZoomFrame::get_Layout()=0
```

## Observaciones


El ejemplo muestra la obtención del elemento Summary Zoom [Section](../../section/) por índice: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Ver también

* Enumeración [ZoomLayout](../../zoomlayout/)
* Clase [ISummaryZoomFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)