---
title: show_value property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/datalabelformat/show_value/
weight: 200
---
## show_value proprietà
Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. 
True visualizza il valore percentuale. False per nasconderlo.
Lettura/scrittura **bool**.

### Osservazioni

Se il genitore di questo oggetto DataLabelFormat è una collezione DataLabelCollection di etichette dati, allora questa proprietà ottiene o imposta il valore predefinito della proprietà ShowValue per le nuove etichette dati nella collezione DataLabelCollection.  
Impostare questa proprietà con un valore imposta anche questo valore alla proprietà ShowValue per tutte le etichette dati nella collezione DataLabelCollection (ad esempio "DataLabels.DefaultDataLabelFormat.ShowValue = val;" causa che tutti DataLabels[i].ShowValue siano uguali a val).

### Definizione:
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```

### Vedi anche
* classe [`DataLabelFormat`](/slides/python-net/it/aspose.slides.charts/datalabelformat)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)