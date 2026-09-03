---
title: get_image method
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/iparagraph/get_image/
weight: 10
---
## get_image {#}
Devuelve una imagen del párrafo.

### Devuelve

Una imagen que contiene el párrafo renderizado, o **None**
             si el párrafo no se puede encontrar en su colección padre, no tiene límites de renderizado válidos, o ocurre un error al renderizar la imagen.



```python
def get_image(self):
    ...
```



## get_image {#float-float}
Devuelve una imagen del párrafo con la escala especificada.

### Devuelve

Una imagen que contiene el párrafo renderizado, o **None**
             si el párrafo no se puede encontrar en su colección padre, no tiene límites de renderizado válidos, o ocurre un error al renderizar la imagen.



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
* clase [`IParagraph`](/slides/python-net/es/aspose.slides/iparagraph)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)