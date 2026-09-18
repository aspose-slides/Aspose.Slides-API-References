---
title: get_image method
second_title: Referência da API Aspose.Slides for Python via .NET
description: 
type: docs
url: /pt/aspose.slides/graphicalobject/get_image/
weight: 30
---
## get_image(self) {#}
Retorna miniatura da forma.
            O tipo de limites da ShapeThumbnailBounds.Shape é usado por padrão.

### Retorno

Miniatura da forma.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Retorna miniatura da forma.

### Retorno

Miniatura da forma ou None caso ShapeThumbnailBounds.Appearance seja usado e uma forma não tenha elementos visíveis.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/pt/aspose.slides/shapethumbnailbounds) | Tipo de limites da ShapeThumbnailBounds. |
| scale_x | **float** | Escala X |
| scale_y | **float** | Escala Y |



### Veja Também
* classe [`GraphicalObject`](/slides/python-net/pt/aspose.slides/graphicalobject)
* classe [`IImage`](/slides/python-net/pt/aspose.slides/iimage)
* enumeração [`ShapeThumbnailBounds`](/slides/python-net/pt/aspose.slides/shapethumbnailbounds)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)