---
title: show_value property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/idatalabelformat/show_value/
weight: 200
---
## show_value propriedade
Representa o comportamento de exibição do valor percentual do rótulo de dados de um gráfico especificado. 
True exibe o valor percentual. False para ocultar.
Leitura/gravação **bool**.

### Observações

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados, então esta
            propriedade obtém ou define o valor padrão da propriedade ShowValue para os novos 
            rótulos de dados na coleção DataLabelCollection.
            Definir esta propriedade com um valor também define esse valor na propriedade ShowValue 
            para todos os rótulos de dados na coleção DataLabelCollection
            (ou seja, "DataLabels.DefaultDataLabelFormat.ShowValue = val;" faz com que 
            todos DataLabels[i].ShowValue sejam iguais a val).

### Definição:
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```

### Veja Também
* classe [`IDataLabelFormat`](/slides/python-net/pt/aspose.slides.charts/idatalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)