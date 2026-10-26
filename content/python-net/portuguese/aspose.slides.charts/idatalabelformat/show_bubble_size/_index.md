---
title: show_bubble_size property
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.charts/idatalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size propriedade
Representa o comportamento de exibição do valor do tamanho da bolha do rótulo de dados de um gráfico especificado. 
            True exibe o valor do tamanho da bolha. False oculta.
            Leitura/gravação **bool**.

### Observações

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados, então esta
            propriedade obtém ou define o valor padrão da propriedade ShowBubbleSize para os novos
            rótulos de dados na coleção DataLabelCollection.
            Definir esta propriedade com um valor também define esse valor na propriedade ShowBubbleSize
            para todos os rótulos de dados na coleção DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" faz com que
            todos DataLabels[i].ShowBubbleSize sejam iguais a val).

### Definição:
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```

### Veja Também
* classe [`IDataLabelFormat`](/slides/python-net/pt/aspose.slides.charts/idatalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)