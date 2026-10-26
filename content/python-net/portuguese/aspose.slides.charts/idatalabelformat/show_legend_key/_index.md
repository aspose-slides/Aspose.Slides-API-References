---
title: show_legend_key property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/idatalabelformat/show_legend_key/
weight: 170
---
## show_legend_key propriedade
Representa o comportamento de exibição da chave da legenda do rótulo de dados de um gráfico especificado. 
            True se a chave da legenda do rótulo de dados estiver visível.
            Leitura/gravação **bool**.


### Observações

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então este
            propriedade obtém ou define o valor padrão da propriedade ShowLegendKey para os novos dados 
            rótulos na coleção DataLabelCollection.
            Defina esta propriedade com um valor também define esse valor na propriedade ShowLegendKey 
            para todos os rótulos de dados na coleção DataLabelCollection
            (ou seja, "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" faz com que 
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
* classe [`IDataLabelFormat`](/slides/python-net/pt/aspose.slides.charts/idatalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)