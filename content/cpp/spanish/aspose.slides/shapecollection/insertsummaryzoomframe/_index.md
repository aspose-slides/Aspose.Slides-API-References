---
title: InsertSummaryZoomFrame()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea un nuevo marco Summary Zoom y lo inserta en la colección de formas en el índice especificado.
type: docs
weight: 170
url: /es/aspose.slides/shapecollection/insertsummaryzoomframe/
---
## ShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) método


Crea un nuevo marco Summary Zoom y lo inserta en la colección de formas en el índice especificado.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que insertar el marco Summary Zoom. |
| x | **float** | La coordenada x del nuevo marco Summary Zoom, en puntos. |
| y | **float** | La coordenada y del nuevo marco Summary Zoom, en puntos. |
| width | **float** | El ancho del nuevo marco Summary Zoom, en puntos. |
| height | **float** | La altura del nuevo marco Summary Zoom, en puntos. |

### Valor de retorno

El [ISummaryZoomFrame](../../isummaryzoomframe/) recién creado.
## Comentarios


Este método crea un marco Summary Zoom que agrupa enlaces de resumen para todas las secciones de la presentación. 

Este ejemplo demuestra la creación e inserción de un objeto Summary Zoom en el índice especificado de una colección (asuma que hay al menos dos secciones en la presentación "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```


## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISummaryZoomFrame](../../isummaryzoomframe/)
* Clase [ShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)