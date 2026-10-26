---
title: show_legend_key property
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides.charts/datalabelformat/show_legend_key/
weight: 170
---
## show_legend_key propriedade
Representa o comportamento de exibição da chave de legenda do rótulo de dados de um gráfico especificado. 
            Verdadeiro se a chave de legenda do rótulo de dados estiver visível.
            Leitura/Gravação **bool**.


### Observações

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta
            propriedade obtém ou define o valor padrão da propriedade ShowLegendKey para os novos 
            rótulos na coleção DataLabelCollection.
            Definir esta propriedade com valor também define esse valor para a propriedade ShowLegendKey 
            de todos os rótulos na coleção DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" faz com que 
            todos DataLabels[i].ShowLegendKey sejam iguais a val).

### Definição:
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```


### Veja também
* classe [`DataLabelFormat`](/slides/python-net/pt/aspose.slides.charts/datalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)