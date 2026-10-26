---
title: write_shape_end method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/
weight: 30
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
Chamado antes da renderização da forma. Chamado uma vez por cada forma. Se esta função escreve algo no gerador, a geração da imagem do slide atual será concluída, o fragmento html adicionado será inserido e uma nova imagem será iniciada sobre a anterior.

```python
def write_shape_end(self, generator, shape):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/pt/aspose.slides.export/ihtmlgenerator) | Objeto de saída. |
| shape | [`IShape`](/slides/python-net/pt/aspose.slides/ishape) | Forma que é renderizada por último. |

### Veja Também
* classe [`IHtmlFormattingController`](/slides/python-net/pt/aspose.slides.export/ihtmlformattingcontroller)
* classe [`IHtmlGenerator`](/slides/python-net/pt/aspose.slides.export/ihtmlgenerator)
* classe [`IShape`](/slides/python-net/pt/aspose.slides/ishape)
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)