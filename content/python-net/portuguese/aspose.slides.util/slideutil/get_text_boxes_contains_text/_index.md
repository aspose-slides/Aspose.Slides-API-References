---
title: get_text_boxes_contains_text method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.util/slideutil/get_text_boxes_contains_text/
weight: 70
---
## get_text_boxes_contains_text(slide, text, check_placeholder_text) {#ibaseslide-str-bool}
Retorna todos os quadros de texto no slide especificado que contêm o texto fornecido.

### Retorna

Um array de [`ITextFrame`](/slides/python-net/pt/aspose.slides/itextframe) objetos que contêm o texto especificado.



```python
@staticmethod
def get_text_boxes_contains_text(slide, text, check_placeholder_text):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide) | O slide a ser pesquisado. |
| text | **str** | O texto a ser pesquisado dentro dos quadros de texto. |
| check_placeholder_text | **bool** | Indica se devem ser incluídos quadros de texto que estejam vazios, mas cujo texto de espaço reservado contenha o texto de pesquisa. |



### Ver também
* classe [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide)
* classe [`ITextFrame`](/slides/python-net/pt/aspose.slides/itextframe)
* classe [`SlideUtil`](/slides/python-net/pt/aspose.slides.util/slideutil)
* módulo [`aspose.slides.util`](/slides/python-net/pt/aspose.slides.util)
* biblioteca [`Aspose.Slides`](/slides/python-net)