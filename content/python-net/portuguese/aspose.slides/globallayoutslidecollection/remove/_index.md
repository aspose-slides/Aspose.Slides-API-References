---
title: remove method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/globallayoutslidecollection/remove/
weight: 40
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

1) Para evitar a exceção PptxEditException, verifique a propriedade HasDependingSlides do layout antes.
2) Você também pode usar o método [`ILayoutSlide.remove`](/slides/python-net/pt/aspose.slides/ilayoutslide/remove) para simplificar o código.

### Exceções

| Exceção | Descrição |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception) | Lançada se o layout for usado na apresentação (sua propriedade HasDependingSlides for verdadeira). |



### Veja Também
* classe [`GlobalLayoutSlideCollection`](/slides/python-net/pt/aspose.slides/globallayoutslidecollection)
* classe [`ILayoutSlide`](/slides/python-net/pt/aspose.slides/ilayoutslide)
* classe [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)