---
title: show_legend_key property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/datalabelformat/show_legend_key/
weight: 170
---
## show_legend_key proprietà
Rappresenta il comportamento di visualizzazione della chiave della leggenda dell'etichetta dati di un grafico specificato.  
True se la chiave della leggenda dell'etichetta dati è visibile.  
Lettura/Scrittura **bool**.

### Osservazioni

Se il genitore di questo oggetto DataLabelFormat è una collezione DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLegendKey per le nuove etichette dati nella collezione DataLabelCollection.  
Impostare questa proprietà con un valore imposta anche questo valore nella proprietà ShowLegendKey per tutte le etichette dati nella collezione DataLabelCollection (ad esempio "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" fa sì che tutti i DataLabels[i].ShowLegendKey siano uguali a val).

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
* classe [`DataLabelFormat`](/slides/python-net/it/aspose.slides.charts/datalabelformat)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)