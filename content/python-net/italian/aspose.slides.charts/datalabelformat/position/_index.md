---
title: position property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/datalabelformat/position/
weight: 90
---
## position proprietà
Rappresenta la posizione dell'etichetta dei dati.
            Lettura/scrittura [`LegendDataLabelPosition`](/slides/python-net/it/aspose.slides.charts/legenddatalabelposition).

### Osservazioni

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, allora questa
            proprietà ottiene o imposta il valore predefinito della proprietà Position per le nuove etichette
            nella raccolta DataLabelCollection.
            Rappresenta la posizione per gli oggetti DataLabel.
            Impostare questa proprietà con valore imposta anche questo valore nella proprietà Position
            per tutte le etichette nella raccolta DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.Position = val;" causa che
            tutti i DataLabels[i].Position siano uguali a val).

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
* classe [`DataLabelFormat`](/slides/python-net/it/aspose.slides.charts/datalabelformat)
* enumerazione [`LegendDataLabelPosition`](/slides/python-net/it/aspose.slides.charts/legenddatalabelposition)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)