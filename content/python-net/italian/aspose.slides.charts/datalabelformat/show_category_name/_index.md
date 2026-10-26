---
title: show_category_name property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/datalabelformat/show_category_name/
weight: 130
---
## show_category_name proprietà
Rappresenta il comportamento di visualizzazione del nome della categoria delle etichette dati di un grafico specificato.
            True per visualizzare il nome della categoria per le etichette dati su un grafico. False per nascondere.
            Lettura/scrittura **bool**.

### Note

Se il genitore di questo oggetto DataLabelFormat è una collezione DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowCategoryName per le nuove etichette dati nella collezione DataLabelCollection.
            Impostare questa proprietà con valore imposta anche questo valore sulla proprietà ShowCategoryName per tutte le etichette dati nella collezione DataLabelCollection (i.e. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" cause to all DataLabels[i].ShowCategoryName is equal to val).

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
* classe [`DataLabelFormat`](/slides/python-net/it/aspose.slides.charts/datalabelformat)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)