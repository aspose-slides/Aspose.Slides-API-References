---
title: set_size method
second_title: Referencia de la API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/slidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Establece el tamaño de la diapositiva por tipo y escala el contenido existente.


```python
def set_size(self, type, scale_type):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/es/aspose.slides/slidesizetype) | El tamaño de diapositiva predefinido que se aplicará. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/es/aspose.slides/slidesizescaletype) | El modo de escalado del contenido a usar. |

### Comentarios

Asignar cualquier valor distinto de [`SlideSizeType.CUSTOM`](/slides/python-net/es/aspose.slides/slidesizetype/CUSTOM) ajusta el [`SlideSize.size`](/slides/python-net/es/aspose.slides/slidesize/size) según el tipo seleccionado, mientras se conserva [`SlideSize.orientation`](/slides/python-net/es/aspose.slides/slidesize/orientation).


## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Establece las dimensiones de la diapositiva explícitamente y escala el contenido existente.


```python
def set_size(self, width, height, scale_type):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | **float** | El nuevo ancho de la diapositiva, en puntos. |
| height | **float** | El nuevo alto de la diapositiva, en puntos. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/es/aspose.slides/slidesizescaletype) | El modo de escalado del contenido a usar. |

### Comentarios

Esto restablece la propiedad [`SlideSize.type`](/slides/python-net/es/aspose.slides/slidesize/type) a [`SlideSizeType.CUSTOM`](/slides/python-net/es/aspose.slides/slidesizetype/CUSTOM) y establece el [`SlideSize.orientation`](/slides/python-net/es/aspose.slides/slidesize/orientation).



### Ver también
* clase [`SlideSize`](/slides/python-net/es/aspose.slides/slidesize)
* enumeración [`SlideSizeScaleType`](/slides/python-net/es/aspose.slides/slidesizescaletype)
* enumeración [`SlideSizeType`](/slides/python-net/es/aspose.slides/slidesizetype)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)