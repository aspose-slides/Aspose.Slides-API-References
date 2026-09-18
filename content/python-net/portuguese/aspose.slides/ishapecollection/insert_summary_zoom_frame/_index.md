---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/ishapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
Cria um novo quadro Summary Zoom e o insere na coleção de formas no índice especificado.

### Retorna

O [`ISummaryZoomFrame`](/slides/python-net/pt/aspose.slides/isummaryzoomframe) recém-criado.

```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| index | **int** | O índice baseado em zero onde inserir o quadro Summary Zoom. |
| x | **float** | A coordenada x do novo quadro Summary Zoom, em pontos. |
| y | **float** | A coordenada y do novo quadro Summary Zoom, em pontos. |
| width | **float** | A largura do novo quadro Summary Zoom, em pontos. |
| height | **float** | A altura do novo quadro Summary Zoom, em pontos. |

### Observações

Este método cria um quadro Summary Zoom que agrega links de resumo para todas as seções da apresentação.

### Exceções

| Exceção | Descrição |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception) | Lançado se a apresentação não contém seções, ou se o slide de destino não pertence a nenhuma seção. |

### Veja Também
* classe [`IShapeCollection`](/slides/python-net/pt/aspose.slides/ishapecollection)
* classe [`ISummaryZoomFrame`](/slides/python-net/pt/aspose.slides/isummaryzoomframe)
* classe [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)