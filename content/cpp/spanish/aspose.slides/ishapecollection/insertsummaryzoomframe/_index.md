---
title: InsertSummaryZoomFrame()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo marco Summary Zoom y lo inserta en la colección de formas en el índice especificado.
type: docs
weight: 157
url: /es/aspose.slides/ishapecollection/insertsummaryzoomframe/
---
## IShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) método

Crea un nuevo marco Summary Zoom y lo inserta en la colección de formas en el índice especificado.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se insertará el marco Summary Zoom. |
| x | **float** | La coordenada x del nuevo marco Summary Zoom, en puntos. |
| y | **float** | La coordenada y del nuevo marco Summary Zoom, en puntos. |
| width | **float** | El ancho del nuevo marco Summary Zoom, en puntos. |
| height | **float** | La altura del nuevo marco Summary Zoom, en puntos. |

### Valor devuelto

El [ISummaryZoomFrame](../../isummaryzoomframe/) creado recientemente.

## Observaciones

Este método crea un marco Summary Zoom que agrega enlaces de resumen para todas las secciones de la presentación.

Este ejemplo muestra la creación e inserción de un objeto Summary Zoom en el índice especificado de una colección (suponga que hay al menos dos secciones en la presentación "Presentation.pptx"):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISummaryZoomFrame](../../isummaryzoomframe/)
* Clase [IShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)