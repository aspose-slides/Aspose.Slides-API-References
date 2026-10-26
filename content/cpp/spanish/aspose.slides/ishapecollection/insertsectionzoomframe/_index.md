---
title: InsertSectionZoomFrame()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo marco Section Zoom e lo inserta en la colección de shapes en el índice especificado.
type: docs
weight: 131
url: /es/aspose.slides/ishapecollection/insertsectionzoomframe/
---
## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) método


Crea un nuevo [Section](../../section/) Zoom frame e lo inserta en la colección de shapes en el índice especificado.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se inserta el [Section](../../section/) Zoom frame. |
| x | **float** | La coordenada x del nuevo [Section](../../section/) Zoom frame, en puntos. |
| y | **float** | La coordenada y del nuevo [Section](../../section/) Zoom frame, en puntos. |
| width | **float** | El ancho del nuevo [Section](../../section/) Zoom frame, en puntos. |
| height | **float** | La altura del nuevo [Section](../../section/) Zoom frame, en puntos. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | El [ISection](../../isection/) referenciado por el [Section](../../section/) Zoom frame; debe pertenecer a esta presentación y contener al menos una diapositiva. |

### Valor devuelto

El [ISectionZoomFrame](../../isectionzoomframe/) recién creado.

## Observaciones


Este ejemplo demuestra la creación e inserción de un objeto [Section](../../section/) Zoom en el índice especificado de una colección (asuma que hay al menos dos secciones en la presentación "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) método


Crea un nuevo [Section](../../section/) Zoom frame con una imagen predefinida y lo inserta en la colección de shapes en el índice especificado.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero en el que se inserta el [Section](../../section/) Zoom frame. |
| x | **float** | La coordenada x del nuevo [Section](../../section/) Zoom frame, en puntos. |
| y | **float** | La coordenada y del nuevo [Section](../../section/) Zoom frame, en puntos. |
| width | **float** | El ancho del nuevo [Section](../../section/) Zoom frame, en puntos. |
| height | **float** | La altura del nuevo [Section](../../section/) Zoom frame, en puntos. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | El [ISection](../../isection/) referenciado por el [Section](../../section/) Zoom frame; debe pertenecer a esta presentación y contener al menos una diapositiva. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | La imagen a mostrar dentro del [Section](../../section/) Zoom frame. |

### Valor devuelto

El [ISectionZoomFrame](../../isectionzoomframe/) recién creado.

## Observaciones


Este ejemplo demuestra la creación e inserción de un objeto [Section](../../section/) Zoom en el índice especificado de una colección (asuma que hay al menos dos secciones en la presentación "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISectionZoomFrame](../../isectionzoomframe/)
* Clase [ISection](../../isection/)
* Clase [IShapeCollection](../)
* Clase [IPPImage](../../ippimage/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)