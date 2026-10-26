---
title: set_size method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/slidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Define o tamanho do slide por tipo e dimensiona o conteúdo existente.

```python
def set_size(self, type, scale_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/pt/aspose.slides/slidesizetype) | The predefined slide size to apply. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/pt/aspose.slides/slidesizescaletype) | The content scaling mode to use. |

### Observações

Atribuir qualquer valor diferente de [`SlideSizeType.CUSTOM`](/slides/python-net/pt/aspose.slides/slidesizetype/CUSTOM) ajusta o [`SlideSize.size`](/slides/python-net/pt/aspose.slides/slidesize/size) com base no tipo selecionado, enquanto preserva [`SlideSize.orientation`](/slides/python-net/pt/aspose.slides/slidesize/orientation).

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Define explicitamente as dimensões do slide e dimensiona o conteúdo existente.

```python
def set_size(self, width, height, scale_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| width | **float** | A nova largura do slide, em pontos. |
| height | **float** | A nova altura do slide, em pontos. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/pt/aspose.slides/slidesizescaletype) | O modo de dimensionamento de conteúdo a ser usado. |

### Observações

Isso redefine a propriedade [`SlideSize.type`](/slides/python-net/pt/aspose.slides/slidesize/type) para [`SlideSizeType.CUSTOM`](/slides/python-net/pt/aspose.slides/slidesizetype/CUSTOM) e define o [`SlideSize.orientation`](/slides/python-net/pt/aspose.slides/slidesize/orientation).

### Ver também
* classe [`SlideSize`](/slides/python-net/pt/aspose.slides/slidesize)
* enumeração [`SlideSizeScaleType`](/slides/python-net/pt/aspose.slides/slidesizescaletype)
* enumeração [`SlideSizeType`](/slides/python-net/pt/aspose.slides/slidesizetype)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)