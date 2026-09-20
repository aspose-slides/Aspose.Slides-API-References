---
title: separator property
second_title: Aspose.Slides per Python tramite .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.charts/idatalabelformat/separator/
weight: 110
---
## separator proprietà
Imposta o restituisce un Variant che rappresenta il separatore utilizzato per le etichette dei dati in un grafico.
Lettura/Scrittura **str**.

### Osservazioni

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dei dati, allora questa
proprietà ottiene o imposta il valore predefinito della proprietà Separator per le nuove
etichette nella raccolta DataLabelCollection.
Impostare questa proprietà con un valore imposta anche questo valore alla proprietà Separator
per tutte le etichette dei dati nella raccolta DataLabelCollection
(i.e. "DataLabels.DefaultDataLabelFormat.Separator = val;" cause to
tutte DataLabels[i].Separator sono uguali a val).

### Definizione:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```

### Vedi anche
* classe [`IDataLabelFormat`](/slides/python-net/it/aspose.slides.charts/idatalabelformat)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)