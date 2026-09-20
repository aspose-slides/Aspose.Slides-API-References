---
title: get_images method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/presentation/get_images/
weight: 20
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Restituisce oggetti Image per tutte le diapositive di una presentazione.

### Restituisce

oggetti Image.



```python
def get_images(self, options):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/it/aspose.slides.export/irenderingoptions) | Opzioni Tiff. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Restituisce oggetti Thumbnail Image per le diapositive specificate di una presentazione.

### Restituisce

oggetti Image.



```python
def get_images(self, options, slides):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/it/aspose.slides.export/irenderingoptions) | Opzioni Tiff. |
| slides | **List[int]** | Array con le posizioni delle diapositive, a partire da 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Restituisce oggetti Thumbnail Image per tutte le diapositive di una presentazione con dimensione specificata.

### Restituisce

oggetti Image.



```python
def get_images(self, options, image_size):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/it/aspose.slides.export/irenderingoptions) | Opzioni Tiff. |
| image_size | **aspose.slides.Size** | Dimensione dell'immagine da creare. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Restituisce oggetti Thumbnail Image per tutte le diapositive di una presentazione con ridimensionamento personalizzato.

### Restituisce

oggetti Image.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/it/aspose.slides.export/irenderingoptions) | Opzioni Tiff. |
| scale_x | **float** | Il valore con cui scalare questa Thumbnail nella direzione dell'asse x. |
| scale_y | **float** | Il valore con cui scalare questa Thumbnail nella direzione dell'asse y. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
Restituisce oggetti Thumbnail Image per le diapositive specificate di una presentazione con dimensione specificata.

### Restituisce

oggetti Image.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/it/aspose.slides.export/irenderingoptions) | Opzioni Tiff. |
| slides | **List[int]** | Array con le posizioni delle diapositive, a partire da 1. |
| image_size | **aspose.slides.Size** | Dimensione dell'immagine da creare. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Restituisce oggetti Thumbnail Image per le diapositive specificate di una presentazione con ridimensionamento personalizzato.

### Restituisce

oggetti Image.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/it/aspose.slides.export/irenderingoptions) | Opzioni Tiff. |
| slides | **List[int]** | Array con le posizioni delle diapositive, a partire da 1. |
| scale_x | **float** | Il valore con cui scalare questa Thumbnail nella direzione dell'asse x. |
| scale_y | **float** | Il valore con cui scalare questa Thumbnail nella direzione dell'asse y. |



### Vedi anche
* classe [`IRenderingOptions`](/slides/python-net/it/aspose.slides.export/irenderingoptions)
* classe [`Presentation`](/slides/python-net/it/aspose.slides/presentation)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)