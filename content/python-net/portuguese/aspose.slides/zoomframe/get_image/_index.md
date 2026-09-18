---
title: get_image method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/zoomframe/get_image/
weight: 30
---
## get_image(self) {#}
Retorna a miniatura da forma.
            ShapeThumbnailBounds.Shape tipo de limites da miniatura da forma é usado por padrão.

### Retorna

Miniatura da forma.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Retorna a miniatura da forma.

### Retorna

Miniatura da forma ou None caso ShapeThumbnailBounds.Appearance seja usado e a forma não tenha elementos visíveis.



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
* classe [`IImage`](/slides/python-net/pt/aspose.slides/iimage)
* enumeração [`ShapeThumbnailBounds`](/slides/python-net/pt/aspose.slides/shapethumbnailbounds)
* classe [`ZoomFrame`](/slides/python-net/pt/aspose.slides/zoomframe)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)