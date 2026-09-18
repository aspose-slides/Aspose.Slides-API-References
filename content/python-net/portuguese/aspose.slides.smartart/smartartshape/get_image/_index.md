---
title: get_image method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.smartart/smartartshape/get_image/
weight: 50
---
## get_image(self) {#}
Retorna miniatura da forma.  
O tipo de limites da miniatura da forma ShapeThumbnailBounds.Shape é usado por padrão.

### Retorna

Miniatura da forma.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Retorna miniatura da forma.

### Retorna

Miniatura da forma ou None no caso de ShapeThumbnailBounds.Appearance ser usado e a forma não possuir elementos visíveis.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/pt/aspose.slides/shapethumbnailbounds) | Tipo dos limites da miniatura da forma. |
| scale_x | **float** | Escala X |
| scale_y | **float** | Escala Y |



### Veja Também
* classe [`IImage`](/slides/python-net/pt/aspose.slides/iimage)
* enumeração [`ShapeThumbnailBounds`](/slides/python-net/pt/aspose.slides/shapethumbnailbounds)
* classe [`SmartArtShape`](/slides/python-net/pt/aspose.slides.smartart/smartartshape)
* módulo [`aspose.slides.smartart`](/slides/python-net/pt/aspose.slides.smartart)
* biblioteca [`Aspose.Slides`](/slides/python-net)