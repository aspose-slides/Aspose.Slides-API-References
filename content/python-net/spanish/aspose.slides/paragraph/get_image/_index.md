---
title: get_image method
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/paragraph/get_image/
weight: 20
---
## get_image {#}
Devuelve una imagen del párrafo.

### Devuelve
Una imagen que contiene el párrafo renderizado, o **None**
             si el párrafo no se puede encontrar en su colección principal, no tiene límites de renderizado válidos, o ocurre un error al renderizar la imagen.



```python
def get_image(self):
    ...
```


## get_image {#float-float}
Devuelve una imagen del párrafo con la escala especificada.

### Devuelve
Una imagen que contiene el párrafo renderizado, o **None**
             si el párrafo no se puede encontrar en su colección principal, no tiene límites de renderizado válidos, o ocurre un error al renderizar la imagen.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| scale_x | **float** | El factor de escala horizontal aplicado a la imagen del párrafo. |
| scale_y | **float** | El factor de escala vertical aplicado a la imagen del párrafo. |



### Ver también
* clase [`IImage`](/slides/python-net/es/aspose.slides/iimage)
* clase [`Paragraph`](/slides/python-net/es/aspose.slides/paragraph)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)