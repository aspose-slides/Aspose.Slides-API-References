---
title: get_image method
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides.charts/chart/get_image/
weight: 40
---
## get_image(self) {#}
Retorna a miniatura da forma.  
            O tipo de limites da miniatura da forma ShapeThumbnailBounds.Shape é usado por padrão.

### Retorna

Miniatura da forma.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Retorna a miniatura da forma.

### Retorna

Miniatura da forma ou None no caso de ShapeThumbnailBounds.Appearance ser usado e a forma não possuir elementos visíveis.



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
* classe [`Chart`](/slides/python-net/pt/aspose.slides.charts/chart)
* classe [`IImage`](/slides/python-net/pt/aspose.slides/iimage)
* enumeração [`ShapeThumbnailBounds`](/slides/python-net/pt/aspose.slides/shapethumbnailbounds)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)