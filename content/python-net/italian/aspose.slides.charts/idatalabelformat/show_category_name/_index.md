---
title: show_category_name property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/idatalabelformat/show_category_name/
weight: 130
---
## show_category_name proprietà
Rappresenta il comportamento di visualizzazione del nome della categoria dell'etichetta dati di un grafico specificato.
True per visualizzare il nome della categoria per le etichette dati su un grafico. False per nascondere.
Lettura/scrittura **bool**.

### Osservazioni

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, allora questa proprietà ottiene o imposta il valore predefinito della proprietà ShowCategoryName per le nuove etichette dati nella raccolta DataLabelCollection.
Impostare questa proprietà con un valore imposta anche questo valore sulla proprietà ShowCategoryName per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" causa che tutte le DataLabels[i].ShowCategoryName siano uguali a val).

### Definizione:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```

### Vedi anche
* classe [`IDataLabelFormat`](/slides/python-net/it/aspose.slides.charts/idatalabelformat)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)