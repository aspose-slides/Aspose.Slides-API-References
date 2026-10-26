---
title: show_bubble_size property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/datalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size proprietà
Rappresenta il comportamento di visualizzazione del valore della dimensione della bolla dell'etichetta dati di un grafico specificato. 
            True visualizza il valore della dimensione della bolla. False per nascondere.
            Lettura/scrittura **bool**.

### Osservazioni
Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, allora questa proprietà ottiene o imposta il valore predefinito della proprietà ShowBubbleSize per le nuove etichette dati nella raccolta DataLabelCollection. 
            Impostare questa proprietà con un valore imposta anche questo valore nella proprietà ShowBubbleSize per tutte le etichette dati nella raccolta DataLabelCollection 
            (ad esempio "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" causa che 
            tutte le DataLabels[i].ShowBubbleSize siano uguali a val).

### Definizione:
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```

### Vedi anche
* classe [`DataLabelFormat`](/slides/python-net/it/aspose.slides.charts/datalabelformat)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)