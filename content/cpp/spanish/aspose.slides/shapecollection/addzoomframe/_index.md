---
title: AddZoomFrame()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo Zoom frame y lo agrega al final de la colección de formas.
type: docs
weight: 105
url: /es/aspose.slides/shapecollection/addzoomframe/
---
## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) método


Crea un nuevo Zoom frame y lo agrega al final de la colección de formas.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada x del nuevo Zoom frame, en puntos. |
| y | **float** | La coordenada y del nuevo Zoom frame, en puntos. |
| width | **float** | El ancho del nuevo Zoom frame, en puntos. |
| height | **float** | La altura del nuevo Zoom frame, en puntos. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | El [ISlide](../../islide/) referenciado por el Zoom frame; debe pertenecer a esta presentación. |

### Valor de retorno

El [IZoomFrame](../../izoomframe/) recién creado.

## Observaciones


Este ejemplo muestra cómo agregar un objeto Zoom al final de una colección (suponga que hay al menos dos diapositivas en la presentación "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) método


Crea un nuevo Zoom frame y lo agrega al final de la colección de formas.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada x del nuevo Zoom frame, en puntos. |
| y | **float** | La coordenada y del nuevo Zoom frame, en puntos. |
| width | **float** | El ancho del nuevo Zoom frame, en puntos. |
| height | **float** | La altura del nuevo Zoom frame, en puntos. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | El [ISlide](../../islide/) referenciado por el Zoom frame; debe pertenecer a esta presentación. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | La imagen para la diapositiva referenciada [IPPImage](../../ippimage/). |

### Valor de retorno

El [IZoomFrame](../../izoomframe/) recién creado.

## Observaciones


Este ejemplo muestra cómo agregar un objeto Zoom al final de una colección (suponga que hay al menos dos diapositivas en la presentación "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```




## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [ShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)