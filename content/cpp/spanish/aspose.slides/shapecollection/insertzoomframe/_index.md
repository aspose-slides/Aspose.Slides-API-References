---
title: InsertZoomFrame()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo marco Zoom y lo inserta en la colección de formas en el índice especificado.
type: docs
weight: 118
url: /es/aspose.slides/shapecollection/insertzoomframe/
---
## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) método

Crea un nuevo marco Zoom y lo inserta en la colección de formas en el índice especificado.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero donde se insertará el marco Zoom. |
| x | **float** | La coordenada x del nuevo marco Zoom, en puntos. |
| y | **float** | La coordenada y del nuevo marco Zoom, en puntos. |
| width | **float** | El ancho del nuevo marco Zoom, en puntos. |
| height | **float** | El alto del nuevo marco Zoom, en puntos. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | El [ISlide](../../islide/) referenciado por el marco Zoom. |

### Valor devuelto

El [IZoomFrame](../../izoomframe/) recién creado.

## Comentarios

Este ejemplo muestra la creación e inserción de un objeto Zoom en el índice especificado de una colección (asuma que hay al menos dos diapositivas en la presentación \"Presentation.pptx\"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) método

Crea un nuevo marco Zoom con una imagen predefinida y lo inserta en la colección de formas en el índice especificado.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero donde se insertará el marco Zoom. |
| x | **float** | La coordenada x del nuevo marco Zoom, en puntos. |
| y | **float** | La coordenada y del nuevo marco Zoom, en puntos. |
| width | **float** | El ancho del nuevo marco Zoom, en puntos. |
| height | **float** | El alto del nuevo marco Zoom, en puntos. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | El [ISlide](../../islide/) referenciado por el marco Zoom. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | La imagen para la diapositiva referenciada [IPPImage](../../ippimage/). |

### Valor devuelto

El [IZoomFrame](../../izoomframe/) recién creado.

## Comentarios

Este ejemplo muestra la creación e inserción de un objeto Zoom en el índice especificado de una colección (asuma que hay al menos dos diapositivas en la presentación \"Presentation.pptx\"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IZoomFrame](../../izoomframe/)
* Clase [ISlide](../../islide/)
* Clase [ShapeCollection](../)
* Clase [IPPImage](../../ippimage/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)