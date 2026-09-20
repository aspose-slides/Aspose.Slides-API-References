---
title: show_label_value_from_cell property
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.charts/datalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell proprietà
Rappresenta il comportamento di visualizzazione del valore della cella dell'etichetta dati di un grafico specificato. 
            True visualizza il valore della cella. False per nascondere.
            Lettura/scrittura **bool**.

### Osservazioni

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, allora questa
            proprietà ottiene o imposta il valore predefinito della proprietà ShowLabelValueFromCell per le nuove etichette 
            dati nella raccolta DataLabelCollection.
            Impostare questa proprietà con un valore imposta anche questo valore sulla proprietà ShowLabelValueFromCell 
            per tutte le etichette dati nella raccolta DataLabelCollection
            (ad esempio "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" fa sì che 
            tutti DataLabels[i].ShowLabelValueFromCell siano uguali a val).

### Definizione:
```python
@property
def show_label_value_from_cell(self):
    ...

@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```

### Vedi anche
* classe [`DataLabelFormat`](/slides/python-net/it/aspose.slides.charts/datalabelformat)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)