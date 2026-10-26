---
title: separator property
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.charts/datalabelformat/separator/
weight: 110
---
## proprietà separator
Imposta o restituisce un Variant che rappresenta il separator utilizzato per le etichette dei dati in un grafico.
            Lettura/scrittura **str**.


### Osservazioni

Se il genitore di questo oggetto DataLabelFormat è una collezione DataLabelCollection di etichette dei dati, allora questa proprietà ottiene o imposta il valore predefinito della proprietà Separator per le nuove etichette dei dati nella collezione DataLabelCollection.
            Impostare questa proprietà con valore imposta anche questo valore nella proprietà Separator per tutte le etichette dei dati nella collezione DataLabelCollection
            (ad es. "DataLabels.DefaultDataLabelFormat.Separator = val;" causa che tutti i DataLabels[i].Separator siano uguali a val).

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
* classe [`DataLabelFormat`](/slides/python-net/it/aspose.slides.charts/datalabelformat)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)