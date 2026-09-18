---
title: remove method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/masterlayoutslidecollection/remove/
weight: 60
---
## remove(self, value) {#ilayoutslide}
Remove um layout da coleção.


```python
def remove(self, value):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/pt/aspose.slides/ilayoutslide) | O slide de layout a ser removido da coleção. |

### Observações

1) Para evitar a geração da PptxEditException, verifique a propriedade HasDependingSlides do layout antes.
2) Você também pode usar o método [`ILayoutSlide.remove`](/slides/python-net/pt/aspose.slides/ilayoutslide/remove) para simplificar o código.

### Exceções

| Exceção | Descrição |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception) | Lançada se o layout for usado na apresentação (sua propriedade HasDependingSlides for true). |



### Veja Também
* classe [`ILayoutSlide`](/slides/python-net/pt/aspose.slides/ilayoutslide)
* classe [`MasterLayoutSlideCollection`](/slides/python-net/pt/aspose.slides/masterlayoutslidecollection)
* classe [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)