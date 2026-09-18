---
title: show_label_value_from_cell property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/datalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell propriedade
Representa o comportamento de exibição do valor da célula do rótulo de dados de um gráfico especificado. 
True exibe o valor da célula. False para ocultar.
Leitura/gravação **bool**.


### Observações

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados, então esta
propriedade obtém ou define o valor padrão da propriedade ShowLabelValueFromCell para os novos rótulos
de dados na coleção DataLabelCollection.
Definir esta propriedade com um valor também define esse valor na propriedade ShowLabelValueFromCell
para todos os rótulos de dados na coleção DataLabelCollection
(i.e. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" faz com que
todos DataLabels[i].ShowLabelValueFromCell sejam iguais a val).

### Definição:
```python
@property
def show_label_value_from_cell(self):
    ...

@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```


### Veja também
* classe [`DataLabelFormat`](/slides/python-net/pt/aspose.slides.charts/datalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)