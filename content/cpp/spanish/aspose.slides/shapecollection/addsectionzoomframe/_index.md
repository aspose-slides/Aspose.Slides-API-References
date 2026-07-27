---
title: AddSectionZoomFrame()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo marco Section Zoom y lo añade al final de la colección de formas.
type: docs
weight: 131
url: /es/aspose.slides/shapecollection/addsectionzoomframe/
---
## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) método


Crea un nuevo [Section](../../section/) marco de Zoom y lo añade al final de la colección de formas.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada x del nuevo [Section](../../section/) marco de Zoom, en puntos. |
| y | **float** | La coordenada y del nuevo [Section](../../section/) marco de Zoom, en puntos. |
| width | **float** | El ancho del nuevo [Section](../../section/) marco de Zoom, en puntos. |
| height | **float** | La altura del nuevo [Section](../../section/) marco de Zoom, en puntos. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | El [ISection](../../isection/) referenciado por el marco Zoom [Section](../../section/); debe pertenecer a esta presentación y contener al menos una diapositiva. |

### Valor devuelto

El [ISectionZoomFrame](../../isectionzoomframe/) recién creado.

## Observaciones


Este ejemplo muestra cómo añadir un objeto Zoom [Section](../../section/) al final de una colección (asuma que hay al menos dos secciones en la presentación \"Presentation.pptx\"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) método


Crea un nuevo [Section](../../section/) marco de Zoom con una imagen predefinida y lo añade al final de la colección de formas.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada x del nuevo [Section](../../section/) marco de Zoom, en puntos. |
| y | **float** | La coordenada y del nuevo [Section](../../section/) marco de Zoom, en puntos. |
| width | **float** | El ancho del nuevo [Section](../../section/) marco de Zoom, en puntos. |
| height | **float** | La altura del nuevo [Section](../../section/) marco de Zoom, en puntos. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | El [ISection](../../isection/) referenciado por el marco Zoom [Section](../../section/); debe pertenecer a esta presentación y contener al menos una diapositiva. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | La [IPPImage](../../ippimage/) que se mostrará dentro del marco Zoom [Section](../../section/). |

### Valor devuelto

El [ISectionZoomFrame](../../isectionzoomframe/) recién creado.

## Observaciones


Este ejemplo muestra cómo añadir un objeto Zoom [Section](../../section/) al final de una colección (asuma que hay al menos dos secciones en la presentación \"Presentation.pptx\"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISectionZoomFrame](../../isectionzoomframe/)
* Clase [ISection](../../isection/)
* Clase [ShapeCollection](../)
* Clase [IPPImage](../../ippimage/)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)