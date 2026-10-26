---
title: remove method
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/layoutslide/remove/
weight: 60
---
## remove(self) {#}
Remove o layout da apresentação.


```python
def remove(self):
    ...
```


### Observações

Para evitar a ocorrência de PptxEditException, verifique a propriedade HasDependingSlides do layout antes.

### Exceções

| Exceção | Descrição |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception) | Lançada se o layout já foi removido da apresentação ou se o layout está sendo usado na apresentação (sua <br/>            HasDependingSlides property é true). |



### Veja Também
* classe [`LayoutSlide`](/slides/python-net/pt/aspose.slides/layoutslide)
* classe [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)