---
title: InsertSectionZoomFrame()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea un nuevo marco Section Zoom y lo inserta en la colección de formas en el índice especificado.
type: docs
weight: 144
url: /es/aspose.slides/shapecollection/insertsectionzoomframe/
---
## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) método


Crea un nuevo [Section](../../section/) marco de Zoom y lo inserta en la colección de formas en el índice especificado.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se inserta el marco Zoom [Section](../../section/). |
| x | **float** | La coordenada x del nuevo marco Zoom [Section](../../section/), en puntos. |
| y | **float** | La coordenada y del nuevo marco Zoom [Section](../../section/), en puntos. |
| width | **float** | El ancho del nuevo marco Zoom [Section](../../section/), en puntos. |
| height | **float** | La altura del nuevo marco Zoom [Section](../../section/), en puntos. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | El [ISection](../../isection/) referenciado por el marco Zoom [Section](../../section/); debe pertenecer a esta presentación y contener al menos una diapositiva. |

### Valor de retorno

El [ISectionZoomFrame](../../isectionzoomframe/) recién creado.

## Comentarios


Este ejemplo muestra la creación e inserción de un objeto Zoom [Section](../../section/) en el índice especificado de una colección (suponga que hay al menos dos secciones en la presentación "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) método


Crea un nuevo [Section](../../section/) marco de Zoom con una imagen predefinida y lo inserta en la colección de formas en el índice especificado.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se inserta el marco Zoom [Section](../../section/). |
| x | **float** | La coordenada x del nuevo marco Zoom [Section](../../section/), en puntos. |
| y | **float** | La coordenada y del nuevo marco Zoom [Section](../../section/), en puntos. |
| width | **float** | El ancho del nuevo marco Zoom [Section](../../section/), en puntos. |
| height | **float** | La altura del nuevo marco Zoom [Section](../../section/), en puntos. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | El [ISection](../../isection/) referenciado por el marco Zoom [Section](../../section/); debe pertenecer a esta presentación y contener al menos una diapositiva. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | La imagen a mostrar dentro del marco Zoom [Section](../../section/). |

### Valor de retorno

El [ISectionZoomFrame](../../isectionzoomframe/) recién creado.

## Comentarios


Este ejemplo muestra la creación e inserción de un objeto Zoom [Section](../../section/) en el índice especificado de una colección (suponga que hay al menos dos secciones en la presentación "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)