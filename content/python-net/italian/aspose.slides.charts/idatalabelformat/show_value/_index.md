---
title: show_value property
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.charts/idatalabelformat/show_value/
weight: 200
---
## show_value proprietà
Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. 
True visualizza il valore percentuale. False lo nasconde.
Lettura/Scrittura **bool**.


### Osservazioni

Se il genitore di questo oggetto DataLabelFormat è una collezione DataLabelCollection di etichette dati, questa
proprietà ottiene o imposta il valore predefinito della ShowValue Property per le nuove etichette
dati nella collezione DataLabelCollection.
Impostare questa proprietà con un valore imposta lo stesso valore sulla proprietà ShowValue 
per tutte le etichette dati nella collezione DataLabelCollection
(i.e. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" causa che 
tutte le DataLabels[i].ShowValue siano uguali a val).

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
* class [`IDataLabelFormat`](/slides/python-net/it/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)