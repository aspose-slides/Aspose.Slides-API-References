---
title: remove_at method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/masterslidecollection/remove_at/
weight: 40
---
## remove_at(self, index) {#int}
Remove o elemento no índice especificado da coleção.


```python
def remove_at(self, index):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | The zero-based index of the element to remove. |

### Observações

Para evitar o lançamento da PptxEditException, verifique a propriedade HasDependingSlides do mestre antes.

### Exceções

| Exceção | Descrição |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception) | Lançada se o mestre a ser removido for usado na apresentação (sua propriedade HasDependingSlides for verdadeira). |



### Veja Também
* classe [`MasterSlideCollection`](/slides/python-net/pt/aspose.slides/masterslidecollection)
* classe [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)