---
title: number_format property
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.charts/datalabelformat/number_format/
weight: 80
---
## number_format propriedade
Representa a cadeia de caracteres de formato para o objeto DataLabels.
Leitura/gravação **str**.

### Observações

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados, então esta propriedade obtém ou define o valor padrão da propriedade NumberFormat para os novos rótulos de dados na coleção DataLabelCollection.  
Quando esta propriedade é definida com um valor, esse valor também é definido para a propriedade NumberFormat de todos os rótulos de dados na coleção DataLabelCollection (ou seja, "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" faz com que todos DataLabels[i].NumberFormat passem a ser igual a val).

### Definição:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```

### Veja Também
* classe [`DataLabelFormat`](/slides/python-net/pt/aspose.slides.charts/datalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)