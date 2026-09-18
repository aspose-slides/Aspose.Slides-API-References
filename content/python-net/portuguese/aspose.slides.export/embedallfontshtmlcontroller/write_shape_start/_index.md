---
title: write_shape_start method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/
weight: 70
---
## write_shape_start(self, generator, shape) {#ihtmlgenerator-ishape}
Chamado antes da renderização da forma. Chamado uma vez por cada forma. Se esta função escrever algo no generator, a geração da imagem do slide atual será finalizada, o fragmento HTML adicionado será inserido e uma nova imagem será iniciada sobre a anterior.

```python
def write_shape_start(self, generator, shape):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/pt/aspose.slides.export/ihtmlgenerator) | Objeto de saída. |
| shape | [`IShape`](/slides/python-net/pt/aspose.slides/ishape) | Forma que está prestes a ser renderizada. |

### Veja Também
* classe [`EmbedAllFontsHtmlController`](/slides/python-net/pt/aspose.slides.export/embedallfontshtmlcontroller)
* classe [`IHtmlGenerator`](/slides/python-net/pt/aspose.slides.export/ihtmlgenerator)
* classe [`IShape`](/slides/python-net/pt/aspose.slides/ishape)
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)