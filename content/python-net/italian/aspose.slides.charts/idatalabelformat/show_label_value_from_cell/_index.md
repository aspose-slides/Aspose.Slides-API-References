---
title: show_label_value_from_cell property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/idatalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell proprietà
Rappresenta il comportamento di visualizzazione del valore della cella dell'etichetta dati di un grafico specificato. 
True visualizza il valore della cella. False per nascondere.
Lettura/scrittura **bool**.

### Osservazioni

Se il genitore di questo oggetto DataLabelFormat è una collezione DataLabelCollection di etichette dati, allora questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLabelValueFromCell per le nuove etichette dati nella collezione DataLabelCollection. 
Impostare questa proprietà con un valore imposta anche questo valore sulla proprietà ShowLabelValueFromCell per tutte le etichette dati nella collezione DataLabelCollection (ad esempio "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" causa che tutti DataLabels[i].ShowLabelValueFromCell siano uguali a val).

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
* classe [`IDataLabelFormat`](/slides/python-net/it/aspose.slides.charts/idatalabelformat)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)