---
title: get_image method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/videoframe/get_image/
weight: 50
---
## get_image(self) {#}
Retorna miniatura da forma.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type é usado por padrão.

### Returns

Miniatura da forma.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Retorna miniatura da forma.

### Returns

Miniatura da forma ou None no caso em que ShapeThumbnailBounds.Appearance é usado e uma forma não possui elementos visíveis.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/pt/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | escala X |
| scale_y | **float** | escala Y |



### Ver também
* classe [`IImage`](/slides/python-net/pt/aspose.slides/iimage)
* enumeração [`ShapeThumbnailBounds`](/slides/python-net/pt/aspose.slides/shapethumbnailbounds)
* classe [`VideoFrame`](/slides/python-net/pt/aspose.slides/videoframe)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)