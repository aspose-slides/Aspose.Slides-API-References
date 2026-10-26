---
title: get_image method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.ink/inkactions/get_image/
weight: 30
---
## get_image(self) {#}
Retorna miniatura da forma.  
O tipo ShapeThumbnailBounds.Shape de limites da miniatura da forma é usado por padrão.

### Returns
Retorno

Miniatura da forma.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Retorna miniatura da forma.

### Returns
Retorno

Miniatura da forma ou None caso o ShapeThumbnailBounds.Appearance seja usado e a forma não possua elementos visíveis.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/pt/aspose.slides/shapethumbnailbounds) | Tipo de limites da miniatura da forma. |
| scale_x | **float** | Escala X |
| scale_y | **float** | Escala Y |



### See Also
* classe [`IImage`](/slides/python-net/pt/aspose.slides/iimage)
* classe [`InkActions`](/slides/python-net/pt/aspose.slides.ink/inkactions)
* enumeração [`ShapeThumbnailBounds`](/slides/python-net/pt/aspose.slides/shapethumbnailbounds)
* módulo [`aspose.slides.ink`](/slides/python-net/pt/aspose.slides.ink)
* biblioteca [`Aspose.Slides`](/slides/python-net)