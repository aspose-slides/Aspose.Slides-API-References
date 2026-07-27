---
title: get_Layout()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene el diseño de las secciones Summary Zoom en el marco. El valor predeterminado es GridLayout.
type: docs
weight: 1
url: /es/aspose.slides/summaryzoomframe/get_layout/
---
## Método SummaryZoomFrame::get_Layout()


Obtiene el diseño de las secciones Summary Zoom en el marco. El valor predeterminado es GridLayout.

```cpp
ZoomLayout Aspose::Slides::SummaryZoomFrame::get_Layout() override
```

## Observaciones


El ejemplo muestra cómo obtener el elemento Summary Zoom [Section](../../section/) por índice: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Ver también

* Enum [ZoomLayout](../../zoomlayout/)
* Clase [SummaryZoomFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)