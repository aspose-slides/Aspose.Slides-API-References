---
title: show_percentage property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/idatalabelformat/show_percentage/
weight: 180
---
## show_percentage proprietà
Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. 
True visualizza il valore percentuale. False per nasconderlo.
Lettura/scrittura **bool**.


### Osservazioni

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, allora questa proprietà ottiene o imposta il valore predefinito della proprietà ShowPercentage per le nuove etichette dati nella raccolta DataLabelCollection.
Impostare questa proprietà con un valore imposta anche questo valore alla proprietà ShowPercentage per tutte le etichette dati nella raccolta DataLabelCollection
(ad esempio "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" fa sì che tutti i DataLabels[i].ShowPercentage siano uguali a val).

### Definizione:
```python
@property
def show_percentage(self):
    ...

@show_percentage.setter
def show_percentage(self, value):
    ...
```


### Vedi anche
* classe [`IDataLabelFormat`](/slides/python-net/it/aspose.slides.charts/idatalabelformat)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)