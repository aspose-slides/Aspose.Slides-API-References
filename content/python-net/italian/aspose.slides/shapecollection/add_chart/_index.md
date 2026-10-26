---
title: add_chart method
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/shapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
Crea un nuovo grafico, lo inizializza con dati e impostazioni di serie di esempio e lo aggiunge alla fine della collezione di forme.

### Restituisce

Il [`IChart`](/slides/python-net/it/aspose.slides.charts/ichart) appena creato.



```python
def add_chart(self, type, x, y, width, height):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/it/aspose.slides.charts/charttype) | Il tipo di grafico da aggiungere. |
| x | **float** | La coordinata x del nuovo grafico, in punti. |
| y | **float** | La coordinata y del nuovo grafico, in punti. |
| width | **float** | La larghezza del grafico, in punti. |
| height | **float** | L'altezza del grafico, in punti. |


## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
Crea un nuovo grafico, lo inizializza con dati e impostazioni di serie di esempio e lo aggiunge alla fine della collezione di forme.

### Restituisce

Il [`IChart`](/slides/python-net/it/aspose.slides.charts/ichart) appena creato.



```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/it/aspose.slides.charts/charttype) | Il tipo di grafico da aggiungere. |
| x | **float** | La coordinata x del nuovo grafico, in punti. |
| y | **float** | La coordinata y del nuovo grafico, in punti. |
| width | **float** | La larghezza del grafico, in punti. |
| height | **float** | L'altezza del grafico, in punti. |
| init_with_sample | **bool** | True per inizializzare il nuovo grafico con dati e impostazioni di serie di esempio; <br/><br/>            false per creare il grafico senza serie e solo con impostazioni minime, il che rende la creazione<br/><br/>            più veloce. |



### Vedi anche
* enumerazione [`ChartType`](/slides/python-net/it/aspose.slides.charts/charttype)
* classe [`IChart`](/slides/python-net/it/aspose.slides.charts/ichart)
* classe [`ShapeCollection`](/slides/python-net/it/aspose.slides/shapecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)