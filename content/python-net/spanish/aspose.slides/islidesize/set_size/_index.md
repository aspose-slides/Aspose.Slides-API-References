---
title: set_size method
second_title: Referencia de la API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/islidesize/set_size/
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
| type | [`SlideSizeType`](/slides/python-net/es/aspose.slides/slidesizetype) | The predefined slide size to apply. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/es/aspose.slides/slidesizescaletype) | The content scaling mode to use. |

### Remarks
Asignar cualquier valor distinto de [`SlideSizeType.CUSTOM`](/slides/python-net/es/aspose.slides/slidesizetype/CUSTOM) ajusta el [`ISlideSize.size`](/slides/python-net/es/aspose.slides/islidesize/size) según el tipo seleccionado, mientras preserva el [`ISlideSize.orientation`](/slides/python-net/es/aspose.slides/islidesize/orientation).


## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Establece las dimensiones de la diapositiva explícitamente y escala el contenido existente.


```python
def set_size(self, width, height, scale_type):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | **float** | The new slide width, in points. |
| height | **float** | The new slide height, in points. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/es/aspose.slides/slidesizescaletype) | The content scaling mode to use. |

### Remarks
Esto restablece la propiedad [`ISlideSize.type`](/slides/python-net/es/aspose.slides/islidesize/type) a [`SlideSizeType.CUSTOM`](/slides/python-net/es/aspose.slides/slidesizetype/CUSTOM) y establece el [`ISlideSize.orientation`](/slides/python-net/es/aspose.slides/islidesize/orientation).



### Ver también
* clase [`ISlideSize`](/slides/python-net/es/aspose.slides/islidesize)
* enumeración [`SlideSizeScaleType`](/slides/python-net/es/aspose.slides/slidesizescaletype)
* enumeración [`SlideSizeType`](/slides/python-net/es/aspose.slides/slidesizetype)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)