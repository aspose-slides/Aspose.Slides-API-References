---
title: show_percentage property
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.charts/datalabelformat/show_percentage/
weight: 180
---
## show_percentage propriedade
Representa o comportamento de exibição do valor percentual do rótulo de dados de um gráfico especificado. 
True exibe o valor da porcentagem. False para ocultar.
Leitura/gravação **bool**.

### Observações

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados, então esta propriedade obtém ou define o valor padrão da propriedade ShowPercentage para os novos rótulos de dados na coleção DataLabelCollection.
Definir esta propriedade com um valor também define esse valor na propriedade ShowPercentage para todos os rótulos de dados na coleção DataLabelCollection
(i.e. "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" causa que todos DataLabels[i].ShowPercentage sejam iguais a val).

### Definição:
```python
@property
def show_percentage(self):
    ...

@show_percentage.setter
def show_percentage(self, value):
    ...
```

### Ver Também
* classe [`DataLabelFormat`](/slides/python-net/pt/aspose.slides.charts/datalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)