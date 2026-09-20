---
title: position property
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.charts/idatalabelformat/position/
weight: 90
---
## position proprietà
Rappresenta la posizione dell'etichetta dati.
            Lettura/Scrittura [`LegendDataLabelPosition`](/slides/python-net/it/aspose.slides.charts/legenddatalabelposition).


### Osservazioni

Se il genitore di questo oggetto DataLabelFormat è una collezione DataLabelCollection di etichette dati, allora questa
            proprietà ottiene o imposta il valore predefinito della proprietà Position per le nuove etichette
            nella collezione DataLabelCollection.
            Rappresenta la posizione per gli oggetti DataLabel.
            Impostare questa proprietà con un valore imposta anche questo valore nella proprietà Position
            per tutte le etichette dati nella collezione DataLabelCollection
            (ad esempio "DataLabels.DefaultDataLabelFormat.Position = val;" causa che
            tutte le DataLabels[i].Position siano uguali a val).

### Definizione:
```python
@property
def position(self):
    ...

@position.setter
def position(self, value):
    ...
```


### Vedi anche
* classe [`IDataLabelFormat`](/slides/python-net/it/aspose.slides.charts/idatalabelformat)
* enumerazione [`LegendDataLabelPosition`](/slides/python-net/it/aspose.slides.charts/legenddatalabelposition)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)