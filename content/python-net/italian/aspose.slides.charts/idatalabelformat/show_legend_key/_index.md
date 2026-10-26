---
title: show_legend_key property
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.charts/idatalabelformat/show_legend_key/
weight: 170
---
## show_legend_key proprietà
Rappresenta il comportamento di visualizzazione della chiave della legenda dell'etichetta dati di un grafico specificato. 
            True se la chiave della legenda dell'etichetta dati è visibile.
            Lettura/Scrittura **bool**.

### Osservazioni
If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            la proprietà ottiene o imposta il valore predefinito della proprietà ShowLegendKey per le nuove etichette dati 
            nella collezione DataLabelCollection.
            Impostare questa proprietà con valore imposta anche questo valore alla proprietà ShowLegendKey 
            per tutte le etichette dati nella collezione DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" causa a 
            che tutti DataLabels[i].ShowLegendKey siano uguali a val).

### Definizione:
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```

### Vedi anche
* classe [`IDataLabelFormat`](/slides/python-net/it/aspose.slides.charts/idatalabelformat)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)