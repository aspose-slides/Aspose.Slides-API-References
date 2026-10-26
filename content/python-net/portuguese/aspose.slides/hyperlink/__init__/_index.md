---
title: Hyperlink constructor
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/hyperlink/__init__/
weight: 10
---
## __init__(self, url) {#str}
Cria uma instância de um hiperlink.


```python
def __init__(self, url):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| url | **str** | URL do hiperlink. |


## __init__(self, slide) {#islide}
Cria uma instância de um hiperlink que aponta para um slide específico.
            Nota: o hiperlink criado deve ser atribuído a algum objeto da mesma apresentação, caso contrário o link será salvo como NoAction.


```python
def __init__(self, slide):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/pt/aspose.slides/islide) | Slide alvo. |


## __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click) {#hyperlink-str-str-bool-bool-bool}
Cria uma instância de um hiperlink usando outro hiperlink como origem, substituindo propriedades secundárias.


```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/pt/aspose.slides/hyperlink) | Hiperlink de origem |
| target_frame | **str** | Quadro de destino |
| tooltip | **str** | Texto da dica |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |



### Veja Também
* classe [`Hyperlink`](/slides/python-net/pt/aspose.slides/hyperlink)
* classe [`ISlide`](/slides/python-net/pt/aspose.slides/islide)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)