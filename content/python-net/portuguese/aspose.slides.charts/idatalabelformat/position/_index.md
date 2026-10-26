---
title: position property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/idatalabelformat/position/
weight: 90
---
## propriedade position
Representa a posição do DataLabel.
Leitura/Gravação [`LegendDataLabelPosition`](/slides/python-net/pt/aspose.slides.charts/legenddatalabelposition).

### Observações

If parent of this DataLabelFormat object is a DataLabelCollection collection of DataLabels then this
            property gets or sets the default value of the Position property for the new DataLabels 
            DataLabels na coleção DataLabelCollection.
            Representa a posição para os objetos DataLabel.
            Defina esta propriedade com valor também define esse valor na propriedade Position 
            for all DataLabels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.Position = val;" faz com que 
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
* classe [`IDataLabelFormat`](/slides/python-net/pt/aspose.slides.charts/idatalabelformat)
* enumeração [`LegendDataLabelPosition`](/slides/python-net/pt/aspose.slides.charts/legenddatalabelposition)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)