---
title: show_series_name property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/idatalabelformat/show_series_name/
weight: 190
---
## show_series_name propriedade
Retorna ou define um Boolean para indicar o comportamento de exibição do nome da série nos rótulos de dados de um gráfico. 
            True para exibir o nome da série. False para ocultar.
            Leitura/gravação **bool**.


### Observações

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta
            propriedade obtém ou define o valor padrão da propriedade ShowSeriesName para os novos rótulos 
            de dados na coleção DataLabelCollection.
            Definir esta propriedade com um valor também define esse valor para a propriedade ShowSeriesName 
            para todos os rótulos de dados na coleção DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" faz com que 
            todos DataLabels[i].ShowSeriesName sejam iguais a val).

### Definição:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```


### Veja Também
* classe [`IDataLabelFormat`](/slides/python-net/pt/aspose.slides.charts/idatalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)