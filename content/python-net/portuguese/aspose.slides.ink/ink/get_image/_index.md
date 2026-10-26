---
title: get_image method
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides.ink/ink/get_image/
weight: 30
---
## get_image(self) {#}
Retorna miniatura da forma.
            O tipo de limites da miniatura da forma ShapeThumbnailBounds.Shape é usado por padrão.

### Retorno

Miniatura da forma.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Retorna miniatura da forma.

### Retorno

Miniatura da forma ou None caso o ShapeThumbnailBounds.Appearance seja usado e a forma não tenha elementos visíveis.



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
* classe [`Ink`](/slides/python-net/pt/aspose.slides.ink/ink)
* enumeração [`ShapeThumbnailBounds`](/slides/python-net/pt/aspose.slides/shapethumbnailbounds)
* módulo [`aspose.slides.ink`](/slides/python-net/pt/aspose.slides.ink)
* biblioteca [`Aspose.Slides`](/slides/python-net)