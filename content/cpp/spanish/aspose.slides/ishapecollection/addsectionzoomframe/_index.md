---
title: AddSectionZoomFrame()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo marco Zoom de sección y lo agrega al final de la colección de formas.
type: docs
weight: 118
url: /es/aspose.slides/ishapecollection/addsectionzoomframe/
---
## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) método

Crea un nuevo marco Zoom [Section](../../section/) y lo agrega al final de la colección de formas.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada x del nuevo marco Zoom [Section](../../section/), en puntos. |
| y | **float** | La coordenada y del nuevo marco Zoom [Section](../../section/), en puntos. |
| width | **float** | El ancho del nuevo marco Zoom [Section](../../section/), en puntos. |
| height | **float** | La altura del nuevo marco Zoom [Section](../../section/), en puntos. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | El [ISection](../../isection/) referenciado por el marco Zoom [Section](../../section/); debe pertenecer a esta presentación y contener al menos una diapositiva. |

### Valor de retorno

El [ISectionZoomFrame](../../isectionzoomframe/) recién creado.

## Observaciones

Este ejemplo muestra cómo agregar un objeto Zoom [Section](../../section/) al final de una colección (suponga que hay al menos dos secciones en la presentación "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) método

Crea un nuevo marco Zoom [Section](../../section/) con una imagen predefinida y lo agrega al final de la colección de formas.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada x del nuevo marco Zoom [Section](../../section/), en puntos. |
| y | **float** | La coordenada y del nuevo marco Zoom [Section](../../section/), en puntos. |
| width | **float** | El ancho del nuevo marco Zoom [Section](../../section/), en puntos. |
| height | **float** | La altura del nuevo marco Zoom [Section](../../section/), en puntos. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | El [ISection](../../isection/) referenciado por el marco Zoom [Section](../../section/); debe pertenecer a esta presentación y contener al menos una diapositiva. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | El [IPPImage](../../ippimage/) que se mostrará dentro del marco Zoom [Section](../../section/). |

### Valor de retorno

El [ISectionZoomFrame](../../isectionzoomframe/) recién creado.

## Observaciones

Este ejemplo muestra cómo agregar un objeto Zoom [Section](../../section/) al final de una colección (suponga que hay al menos dos secciones en la presentación "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISectionZoomFrame](../../isectionzoomframe/)
* Clase [ISection](../../isection/)
* Clase [IShapeCollection](../)
* Clase [IPPImage](../../ippimage/)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)