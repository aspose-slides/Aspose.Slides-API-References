---
title: remove_at method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/masterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Remove o elemento no índice especificado da coleção.


```python
def remove_at(self, index):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | O índice baseado em zero do elemento a ser removido. |

### Observações

1) Para evitar a exceção PptxEditException, verifique a propriedade HasDependingSlides do layout antes.
2) Você também pode usar o método [`ILayoutSlide.remove`](/slides/python-net/pt/aspose.slides/ilayoutslide/remove) para simplificar o código.

### Exceções

| Exceção | Descrição |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception) | Lançada se o layout for usado na apresentação (sua propriedade HasDependingSlides for true). |

### Veja Também
* classe [`MasterLayoutSlideCollection`](/slides/python-net/pt/aspose.slides/masterlayoutslidecollection)
* classe [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)