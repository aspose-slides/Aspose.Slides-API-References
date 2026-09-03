---
title: get_image method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/iparagraph/get_image/
weight: 10
---
## get_image {#}
Retorna uma imagem do parágrafo.

### Retorna

Uma imagem contendo o parágrafo renderizado, ou **None**
             se o parágrafo não puder ser encontrado na coleção pai, não possuir limites
             de renderização válidos ou ocorrer um erro ao renderizar a imagem.



```python
def get_image(self):
    ...
```



## get_image {#float-float}
Retorna uma imagem do parágrafo com a escala especificada.

### Retorna

Uma imagem contendo o parágrafo renderizado, ou **None**
             se o parágrafo não puder ser encontrado na coleção pai, não possuir limites
             de renderização válidos ou ocorrer um erro ao renderizar a imagem.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| scale_x | **float** | O fator de escala horizontal aplicado à imagem do parágrafo. |
| scale_y | **float** | O fator de escala vertical aplicado à imagem do parágrafo. |



### Veja Também
* classe [`IImage`](/slides/python-net/pt/aspose.slides/iimage)
* classe [`IParagraph`](/slides/python-net/pt/aspose.slides/iparagraph)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)