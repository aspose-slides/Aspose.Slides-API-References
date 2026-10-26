---
title: show_leader_lines property
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.charts/idatalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines proprietà
Rappresenta il comportamento di visualizzazione delle linee guida delle etichette dati di un grafico specificato. 
            True visualizza le linee guida. False le nasconde.
            Lettura/scrittura **bool**.


### Osservazioni

Se il genitore di questo oggetto DataLabelFormat è una collezione DataLabelCollection di etichette dati, allora questa
            proprietà ottiene o imposta il valore predefinito della proprietà ShowLeaderLines per le nuove etichette dati 
            nella collezione DataLabelCollection.
            Imposta questa proprietà con valore imposta anche questo valore sulla proprietà ShowLeaderLines 
            per tutte le etichette dati nella collezione DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" causa a 
            tutti DataLabels[i].ShowLeaderLines è uguale a val).

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
* classe [`IDataLabelFormat`](/slides/python-net/it/aspose.slides.charts/idatalabelformat)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)