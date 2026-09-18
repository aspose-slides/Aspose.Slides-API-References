---
title: get_image method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.smartart/smartart/get_image/
weight: 30
---
## get_image(self) {#}
Retorna miniatura da forma.
            ShapeThumbnailBounds.Shape tipo de limites da miniatura da forma é usado por padrão.

### Retorno

Miniatura da forma.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Retorna miniatura da forma.

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



### Veja Também
* classe [`IImage`](/slides/python-net/pt/aspose.slides/iimage)
* enumeração [`ShapeThumbnailBounds`](/slides/python-net/pt/aspose.slides/shapethumbnailbounds)
* classe [`SmartArt`](/slides/python-net/pt/aspose.slides.smartart/smartart)
* módulo [`aspose.slides.smartart`](/slides/python-net/pt/aspose.slides.smartart)
* biblioteca [`Aspose.Slides`](/slides/python-net)