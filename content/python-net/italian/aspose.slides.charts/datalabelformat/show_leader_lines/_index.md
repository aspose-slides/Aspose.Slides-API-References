---
title: show_leader_lines property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/datalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines proprietà
Rappresenta il comportamento di visualizzazione delle linee guida delle etichette dati di un grafico specificato. 
True visualizza le linee guida. False per nasconderle.
Lettura/scrittura **bool**.

### Osservazioni

Se il genitore di questo oggetto DataLabelFormat è una collezione DataLabelCollection di etichette dati, allora questa
            proprietà ottiene o imposta il valore predefinito della proprietà ShowLeaderLines per le nuove etichette dati 
            etichette nella collezione DataLabelCollection.
            Imposta questa proprietà con valore imposta anche questo valore alla proprietà ShowLeaderLines 
            per tutte le etichette dati nella collezione DataLabelCollection
            (ad es. "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" causa 
            che tutte le DataLabels[i].ShowLeaderLines siano uguali a val).

### Definizione:
```python
@property
def show_leader_lines(self):
    ...

@show_leader_lines.setter
def show_leader_lines(self, value):
    ...
```

### Vedi anche
* classe [`DataLabelFormat`](/slides/python-net/it/aspose.slides.charts/datalabelformat)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)