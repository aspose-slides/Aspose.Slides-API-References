---
title: show_series_name property
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.charts/datalabelformat/show_series_name/
weight: 190
---
## show_series_name proprietà
Restituisce o imposta un Boolean per indicare il comportamento di visualizzazione del nome della serie per le etichette dei dati in un grafico. 
            True per mostrare il nome della serie. False per nascondere.
            Lettura/scrittura **bool**.


### Osservazioni

Se il genitore di questo oggetto DataLabelFormat è una collezione DataLabelCollection di etichette dati, allora questa
            proprietà ottiene o imposta il valore predefinito della proprietà ShowSeriesName per le nuove etichette dati nella collezione DataLabelCollection.
            Impostare questa proprietà con un valore imposta anche tale valore sulla proprietà ShowSeriesName per tutte le etichette dati nella collezione DataLabelCollection
            (ad esempio "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" fa sì che tutti DataLabels[i].ShowSeriesName sia uguale a val).

### Definizione:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```


### Vedi anche
* classe [`DataLabelFormat`](/slides/python-net/it/aspose.slides.charts/datalabelformat)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)