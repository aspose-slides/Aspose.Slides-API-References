---
title: AddZoomFrame()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo marco de Zoom y lo agrega al final de la colección de formas.
type: docs
weight: 92
url: /es/aspose.slides/ishapecollection/addzoomframe/
---
## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) método


Crea un nuevo marco de Zoom y lo agrega al final de la colección de formas.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada x del nuevo marco de Zoom, en puntos. |
| y | **float** | La coordenada y del nuevo marco de Zoom, en puntos. |
| width | **float** | El ancho del nuevo marco de Zoom, en puntos. |
| height | **float** | La altura del nuevo marco de Zoom, en puntos. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | El [ISlide](../../islide/) referenciado por el marco de Zoom; debe pertenecer a esta presentación. |

### Valor devuelto

El [IZoomFrame](../../izoomframe/) recién creado.
## Observaciones


Este ejemplo muestra cómo añadir un objeto Zoom al final de una colección (suponga que hay al menos dos diapositivas en la presentación "Presentation.pptx"): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) método


Crea un nuevo marco de Zoom y lo agrega al final de la colección de formas.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada x del nuevo marco de Zoom, en puntos. |
| y | **float** | La coordenada y del nuevo marco de Zoom, en puntos. |
| width | **float** | El ancho del nuevo marco de Zoom, en puntos. |
| height | **float** | La altura del nuevo marco de Zoom, en puntos. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | El [ISlide](../../islide/) referenciado por el marco de Zoom; debe pertenecer a esta presentación. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | La imagen para la diapositiva referenciada [IPPImage](../../ippimage/). |

### Valor devuelto

El [IZoomFrame](../../izoomframe/) recién creado.
## Observaciones


Este ejemplo muestra cómo añadir un objeto Zoom al final de una colección (suponga que hay al menos dos diapositivas en la presentación "Presentation.pptx"): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```




## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IZoomFrame](../../izoomframe/)
* Clase [ISlide](../../islide/)
* Clase [IShapeCollection](../)
* Clase [IPPImage](../../ippimage/)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)