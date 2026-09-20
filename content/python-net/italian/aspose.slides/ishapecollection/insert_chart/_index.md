---
title: insert_chart method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ishapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni,
            e lo inserisce nella raccolta di forme all'indice specificato.

### Restituisce

Il nuovo [`IChart`](/slides/python-net/it/aspose.slides.charts/ichart) creato.



```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/it/aspose.slides.charts/charttype) | Il tipo di grafico da creare. |
| x | **float** | La coordinata x del nuovo grafico, in punti. |
| y | **float** | La coordinata y del nuovo grafico, in punti. |
| width | **float** | La larghezza del nuovo grafico, in punti. |
| height | **float** | L'altezza del nuovo grafico, in punti. |
| index | **int** | L'indice basato su zero al quale inserire il nuovo grafico nella raccolta di forme. |


## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni,
            e lo inserisce nella raccolta di forme all'indice specificato.

### Restituisce

Il nuovo [`IChart`](/slides/python-net/it/aspose.slides.charts/ichart) creato.



```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/it/aspose.slides.charts/charttype) | Il tipo di grafico da creare. |
| x | **float** | La coordinata x del nuovo grafico, in punti. |
| y | **float** | La coordinata y del nuovo grafico, in punti. |
| width | **float** | La larghezza del nuovo grafico, in punti. |
| height | **float** | L'altezza del nuovo grafico, in punti. |
| index | **int** | L'indice basato su zero al quale inserire il nuovo grafico nella raccolta di forme. |
| init_with_sample | **bool** | True per inizializzare il nuovo grafico con dati di serie di esempio e impostazioni; <br/><br/> false per creare il grafico senza serie e solo con impostazioni minime, il che rende la creazione più veloce. |



### Vedi anche
* enumerazione [`ChartType`](/slides/python-net/it/aspose.slides.charts/charttype)
* classe [`IChart`](/slides/python-net/it/aspose.slides.charts/ichart)
* classe [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)