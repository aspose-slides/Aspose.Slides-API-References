---
title: get_image method
second_title: Aspose.Slides para Python via .NET - Referência da API
description: 
type: docs
url: /pt/aspose.slides/connector/get_image/
weight: 50
---
## get_image(self) {#}
Retorna a miniatura da forma.
O tipo de limite de miniatura da forma ShapeThumbnailBounds.Shape é usado por padrão.

### Returns

Miniatura da forma.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Retorna a miniatura da forma.

### Returns

Miniatura da forma ou None caso ShapeThumbnailBounds.Appearance seja usado e a forma não tenha elementos visíveis.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/pt/aspose.slides/shapethumbnailbounds) | Tipo de limite de miniatura da forma. |
| scale_x | **float** | Escala X |
| scale_y | **float** | Escala Y |



### Veja Também
* classe [`Connector`](/slides/python-net/pt/aspose.slides/connector)
* classe [`IImage`](/slides/python-net/pt/aspose.slides/iimage)
* enumeração [`ShapeThumbnailBounds`](/slides/python-net/pt/aspose.slides/shapethumbnailbounds)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)