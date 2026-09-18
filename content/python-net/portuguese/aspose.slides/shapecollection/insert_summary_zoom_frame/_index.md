---
title: insert_summary_zoom_frame method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/shapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
Cria um novo quadro de resumo de zoom e o insere na coleção de formas no índice especificado.

### Retorno

O [`ISummaryZoomFrame`](/slides/python-net/pt/aspose.slides/isummaryzoomframe) recém-criado.



```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | O índice baseado em zero no qual inserir o quadro de resumo de zoom. |
| x | **float** | A coordenada x do novo quadro de resumo de zoom, em pontos. |
| y | **float** | A coordenada y do novo quadro de resumo de zoom, em pontos. |
| width | **float** | A largura do novo quadro de resumo de zoom, em pontos. |
| height | **float** | A altura do novo quadro de resumo de zoom, em pontos. |

### Observações

Este método cria um quadro de resumo de zoom que agrega links de resumo para todas as seções da apresentação.

### Exceções

| Exceção | Descrição |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception) | Lançada se a apresentação não contiver seções, ou se o slide de destino não pertencer a nenhuma seção. |



### Veja Também
* classe [`ISummaryZoomFrame`](/slides/python-net/pt/aspose.slides/isummaryzoomframe)
* classe [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception)
* classe [`ShapeCollection`](/slides/python-net/pt/aspose.slides/shapecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)