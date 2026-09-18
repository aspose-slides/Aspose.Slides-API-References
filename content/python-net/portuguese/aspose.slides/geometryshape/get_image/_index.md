---
title: get_image method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/geometryshape/get_image/
weight: 50
---
## get_image(self) {#}
Retorna a miniatura da forma.
ShapeThumbnailBounds.Shape tipo de limites da miniatura da forma é usado por padrão.

### Retorno

Miniatura da forma.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Retorna a miniatura da forma.

### Retorno

Miniatura da forma ou None no caso em que ShapeThumbnailBounds.Appearance é usado e uma forma não tem elementos visíveis.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/pt/aspose.slides/shapethumbnailbounds) | Tipo de limites da miniatura da forma. |
| scale_x | **float** | Escala X |
| scale_y | **float** | Escala Y |



### Ver também
* classe [`GeometryShape`](/slides/python-net/pt/aspose.slides/geometryshape)
* classe [`IImage`](/slides/python-net/pt/aspose.slides/iimage)
* enumeração [`ShapeThumbnailBounds`](/slides/python-net/pt/aspose.slides/shapethumbnailbounds)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)