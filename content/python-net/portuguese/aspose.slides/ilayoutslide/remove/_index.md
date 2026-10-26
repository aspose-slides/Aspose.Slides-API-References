---
title: remove method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/ilayoutslide/remove/
weight: 60
---
## remove(self) {#}
Remove o layout da apresentação.

```python
def remove(self):
    ...
```

### Observações

Para evitar a geração da PptxEditException, verifique a propriedade HasDependingSlides do layout antes.

### Exceções

| Exceção | Descrição |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception) | Lançada se o layout já foi removido da apresentação ou se o layout está sendo usado na apresentação (<br/>            sua propriedade HasDependingSlides é true). |

### Veja Também
* classe [`ILayoutSlide`](/slides/python-net/pt/aspose.slides/ilayoutslide)
* classe [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)