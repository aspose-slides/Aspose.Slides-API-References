---
title: separator property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/datalabelformat/separator/
weight: 110
---
## separator propriedade
Define ou retorna um Variant que representa o separator usado para os rótulos de dados em um gráfico.
            Leitura/Gravação **str**.


### Observações

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados, então esta propriedade obtém ou define o valor padrão da propriedade Separator para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor na propriedade Separator para todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.DefaultDataLabelFormat.Separator = val;" faz com que todos DataLabels[i].Separator sejam iguais a val).

### Definição:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```


### Veja Também
* classe [`DataLabelFormat`](/slides/python-net/pt/aspose.slides.charts/datalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)