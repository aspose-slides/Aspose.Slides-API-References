---
title: is_number_format_linked_to_source property
second_title: Referência de API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/datalabelformat/is_number_format_linked_to_source/
weight: 70
---
## is_number_format_linked_to_source propriedade
Leitura/gravação **bool**.

### Observações

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados, então esta
            propriedade obtém ou define o valor padrão da propriedade IsNumberFormatLinkedToSource para os novos rótulos de dados na coleção DataLabelCollection.
            Definir esta propriedade com um valor também define esse valor para a propriedade IsNumberFormatLinkedToSource
            de todos os rótulos de dados na coleção DataLabelCollection
            (ou seja, "DataLabels.DefaultDataLabelFormat.IsNumberFormatLinkedToSource = val;" faz com que
            todos DataLabels[i].IsNumberFormatLinkedToSource sejam iguais a val).

### Definição:
```python
@property
def is_number_format_linked_to_source(self):
    ...

@is_number_format_linked_to_source.setter
def is_number_format_linked_to_source(self, value):
    ...
```

### Veja também
* classe [`DataLabelFormat`](/slides/python-net/pt/aspose.slides.charts/datalabelformat)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)