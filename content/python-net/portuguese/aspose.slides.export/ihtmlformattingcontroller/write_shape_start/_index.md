---
title: write_shape_start method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/
weight: 40
---
## write_shape_start(self, generator, shape) {#ihtmlgenerator-ishape}
Chamado antes da renderização da forma. Chamado uma vez por cada forma. Se esta função escrever algo no gerador, a geração da imagem do slide atual será finalizada, o fragmento html adicionado inserido e uma nova imagem será iniciada sobre a anterior.


```python
def write_shape_start(self, generator, shape):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| generator | [`IHtmlGenerator`](/slides/python-net/pt/aspose.slides.export/ihtmlgenerator) | Objeto de saída. |
| shape | [`IShape`](/slides/python-net/pt/aspose.slides/ishape) | Forma que está prestes a ser renderizada. |



### Ver também
* classe [`IHtmlFormattingController`](/slides/python-net/pt/aspose.slides.export/ihtmlformattingcontroller)
* classe [`IHtmlGenerator`](/slides/python-net/pt/aspose.slides.export/ihtmlgenerator)
* classe [`IShape`](/slides/python-net/pt/aspose.slides/ishape)
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)