---
title: set_size method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/islidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Define o tamanho do slide por tipo e escala o conteúdo existente.


```python
def set_size(self, type, scale_type):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/pt/aspose.slides/slidesizetype) | O tamanho de slide predefinido a ser aplicado. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/pt/aspose.slides/slidesizescaletype) | O modo de escalonamento de conteúdo a ser usado. |

### Observações

Atribuir qualquer valor diferente de [`SlideSizeType.CUSTOM`](/slides/python-net/pt/aspose.slides/slidesizetype/CUSTOM) ajusta o [`ISlideSize.size`](/slides/python-net/pt/aspose.slides/islidesize/size) com base no tipo selecionado, preservando o [`ISlideSize.orientation`](/slides/python-net/pt/aspose.slides/islidesize/orientation).


## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Define as dimensões do slide explicitamente e escala o conteúdo existente.


```python
def set_size(self, width, height, scale_type):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| width | **float** | A nova largura do slide, em pontos. |
| height | **float** | A nova altura do slide, em pontos. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/pt/aspose.slides/slidesizescaletype) | O modo de escalonamento de conteúdo a ser usado. |

### Observações

Isso redefine a propriedade [`ISlideSize.type`](/slides/python-net/pt/aspose.slides/islidesize/type) para [`SlideSizeType.CUSTOM`](/slides/python-net/pt/aspose.slides/slidesizetype/CUSTOM) e define o [`ISlideSize.orientation`](/slides/python-net/pt/aspose.slides/islidesize/orientation).



### Veja também
* classe [`ISlideSize`](/slides/python-net/pt/aspose.slides/islidesize)
* enumeração [`SlideSizeScaleType`](/slides/python-net/pt/aspose.slides/slidesizescaletype)
* enumeração [`SlideSizeType`](/slides/python-net/pt/aspose.slides/slidesizetype)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)