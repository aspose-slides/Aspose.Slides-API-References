---
title: position property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/datalabelformat/position/
weight: 90
---
## propriedade position
Representa a position do rótulo de dados.
Leitura/gravação [`LegendDataLabelPosition`](/slides/python-net/pt/aspose.slides.charts/legenddatalabelposition).

### Observações
Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados, então esta
            propriedade obtém ou define o valor padrão da propriedade Position para os novos
            rótulos de dados na coleção DataLabelCollection.
Representa a position para os objetos DataLabel.
Definir esta propriedade com um valor também define esse valor na propriedade Position
            para todos os rótulos de dados na coleção DataLabelCollection
            (por exemplo, "DataLabels.DefaultDataLabelFormat.Position = val;" faz com que
            todos DataLabels[i].Position sejam iguais a val).

### Definição:
```python
@property
def position(self):
    ...

@position.setter
def position(self, value):
    ...
```

### Veja Também
* classe [`DataLabelFormat`](/slides/python-net/pt/aspose.slides.charts/datalabelformat)
* enumeração [`LegendDataLabelPosition`](/slides/python-net/pt/aspose.slides.charts/legenddatalabelposition)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)