---
title: get_images method
second_title: Riferimento API di Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Restituisce oggetti Thumbnail Image per tutte le slide di una presentazione.

### Restituisce

Bitmap oggetti.



```python
def get_images(self, options):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/it/aspose.slides.export/irenderingoptions) | Opzioni di rendering. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Restituisce oggetti Thumbnail Bitmap per le slide specificate di una presentazione.

### Restituisce

Bitmap oggetti.



```python
def get_images(self, options, slides):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/it/aspose.slides.export/irenderingoptions) | Opzioni di rendering. |
| slides | **List[int]** | Array con le posizioni delle slide, a partire da 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Restituisce oggetti Thumbnail Image per tutte le slide di una presentazione con dimensione specificata.

### Restituisce

Bitmap oggetti.



```python
def get_images(self, options, image_size):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/it/aspose.slides.export/irenderingoptions) | Opzioni di rendering. |
| image_size | **aspose.slides.Size** | Dimensione dell'immagine da creare. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Restituisce oggetti Thumbnail Image per tutte le slide di una presentazione con ridimensionamento personalizzato.

### Restituisce

Bitmap oggetti.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/it/aspose.slides.export/irenderingoptions) | Opzioni di rendering. |
| scale_x | **float** | Il valore con cui scalare questa Thumbnail lungo l'asse x. |
| scale_y | **float** | Il valore con cui scalare questa Thumbnail lungo l'asse y. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
Restituisce oggetti Thumbnail Image per le slide specificate di una presentazione con dimensione specificata.

### Restituisce

Bitmap oggetti.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/it/aspose.slides.export/irenderingoptions) | Opzioni di rendering. |
| slides | **List[int]** | Array con le posizioni delle slide, a partire da 1. |
| image_size | **aspose.slides.Size** | Dimensione dell'immagine da creare. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Restituisce oggetti Thumbnail Image per le slide specificate di una presentazione con ridimensionamento personalizzato.

### Restituisce

Bitmap oggetti.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/it/aspose.slides.export/irenderingoptions) | Opzioni di rendering. |
| slides | **List[int]** | Array con le posizioni delle slide, a partire da 1. |
| scale_x | **float** | Il valore con cui scalare questa Thumbnail lungo l'asse x. |
| scale_y | **float** | Il valore con cui scalare questa Thumbnail lungo l'asse y. |



### Vedi anche
* classe [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation)
* classe [`IRenderingOptions`](/slides/python-net/it/aspose.slides.export/irenderingoptions)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)