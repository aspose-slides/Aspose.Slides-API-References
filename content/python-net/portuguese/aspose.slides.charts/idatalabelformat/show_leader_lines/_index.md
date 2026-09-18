---
title: show_leader_lines property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/idatalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines propriedade
Representa o comportamento de exibição das linhas de guia dos rótulos de dados de um gráfico especificado. 
True exibe as linhas de guia. False para ocultar.
Leitura/gravação **bool**.

### Observações

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados, então esta propriedade obtém ou define o valor padrão da propriedade ShowLeaderLines para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor para a propriedade ShowLeaderLines de todos os rótulos de dados na coleção DataLabelCollection (ou seja, "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" faz com que todos DataLabels[i].ShowLeaderLines sejam iguais a val).

### Definição:
```python
@property
def show_leader_lines(self):
    ...

@show_leader_lines.setter
def show_leader_lines(self, value):
    ...
```

### Veja Também
* classe [`IDataLabelFormat`](/slides/python-net/pt/aspose.slides.charts/idatalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)