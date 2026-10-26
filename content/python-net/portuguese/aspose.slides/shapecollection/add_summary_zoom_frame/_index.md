---
title: add_summary_zoom_frame method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/shapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
Cria um novo quadro Summary Zoom e o adiciona ao final da coleção de shapes.

### Retorna

O [`ISummaryZoomFrame`](/slides/python-net/pt/aspose.slides/isummaryzoomframe) recém-criado.



```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| x | **float** | A coordenada x do novo quadro Summary Zoom, em pontos. |
| y | **float** | A coordenada y do novo quadro Summary Zoom, em pontos. |
| width | **float** | A largura do novo quadro Summary Zoom, em pontos. |
| height | **float** | A altura do novo quadro Summary Zoom, em pontos. |

### Observações

Este método cria um novo Summary Zoom e coloca uma coleção de objetos nele para todas as seções desta apresentação.

### Exceções

| Exceção | Descrição |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception) | Lançada se não houver seções na apresentação, ou se o slide de destino não pertencer a nenhuma seção. |



### Veja Também
* classe [`ISummaryZoomFrame`](/slides/python-net/pt/aspose.slides/isummaryzoomframe)
* classe [`PptxEditException`](/slides/python-net/pt/aspose.slides/pptxeditexception)
* classe [`ShapeCollection`](/slides/python-net/pt/aspose.slides/shapecollection)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)