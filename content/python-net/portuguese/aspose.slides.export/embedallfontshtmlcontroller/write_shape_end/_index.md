---
title: write_shape_end method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/
weight: 60
---
## write_shape_end(self, generator, shape) {#ihtmlgenerator-ishape}
Chamado antes da renderização da shape. Chamado uma vez para cada shape. Se esta função gravar algo no generator, a geração da imagem do slide atual será concluída, o fragmento html adicionado será inserido e uma nova imagem será iniciada sobre a anterior.

```python
def write_shape_end(self, generator, shape):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/pt/aspose.slides.export/ihtmlgenerator) | Objeto de saída. |
| shape | [`IShape`](/slides/python-net/pt/aspose.slides/ishape) | Shape que é renderizado por último. |

### Ver Também
* classe [`EmbedAllFontsHtmlController`](/slides/python-net/pt/aspose.slides.export/embedallfontshtmlcontroller)
* classe [`IHtmlGenerator`](/slides/python-net/pt/aspose.slides.export/ihtmlgenerator)
* classe [`IShape`](/slides/python-net/pt/aspose.slides/ishape)
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)