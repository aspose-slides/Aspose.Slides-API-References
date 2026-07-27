---
title: AddSummaryZoomFrame()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo marco Summary Zoom y lo agrega al final de la colección de formas.
type: docs
weight: 144
url: /es/aspose.slides/ishapecollection/addsummaryzoomframe/
---
## IShapeCollection::AddSummaryZoomFrame(float, float, float, float) método

Crea un nuevo marco Summary Zoom y lo agrega al final de la colección de formas.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada x del nuevo marco Summary Zoom, en puntos. |
| y | **float** | La coordenada y del nuevo marco Summary Zoom, en puntos. |
| width | **float** | El ancho del nuevo marco Summary Zoom, en puntos. |
| height | **float** | La altura del nuevo marco Summary Zoom, en puntos. |

### Valor de retorno

El [ISummaryZoomFrame](../../isummaryzoomframe/) recién creado.

## Observaciones

Este método crea un marco Summary Zoom que agrega enlaces resumen para todas las secciones de la presentación.

Este ejemplo muestra cómo agregar un objeto Summary Zoom al final de una colección (suponga que hay al menos dos secciones en la presentación "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomFrame](../../isummaryzoomframe/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)