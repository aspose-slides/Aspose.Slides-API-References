---
title: number_format property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/idatalabelformat/number_format/
weight: 80
---
## number_format proprietà
Rappresenta la stringa di formato per l'oggetto DataLabels.
            Lettura/scrittura **str**.


### Note

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, allora questa
            proprietà ottiene o imposta il valore predefinito della proprietà NumberFormat per le nuove etichette
            nella raccolta DataLabelCollection.
            Quando questa proprietà viene impostata con un valore, lo stesso valore viene impostato anche per la proprietà NumberFormat di tutte le etichette dati nella raccolta DataLabelCollection
            (es. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" fa sì che tutti i DataLabels[i].NumberFormat siano uguali a val).

### Definizione:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```


### Vedi anche
* classe [`IDataLabelFormat`](/slides/python-net/it/aspose.slides.charts/idatalabelformat)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)