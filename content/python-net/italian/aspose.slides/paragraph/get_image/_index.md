---
title: get_image method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/paragraph/get_image/
weight: 20
---
## get_image {#}
Restituisce un'immagine del paragrafo.

### Restituisce

Un'immagine contenente il paragrafo renderizzato, o **None**
             se il paragrafo non può essere trovato nella sua raccolta padre, non ha limiti di rendering validi,
             oppure si verifica un errore durante il rendering dell'immagine.



```python
def get_image(self):
    ...
```



## get_image {#float-float}
Restituisce un'immagine del paragrafo con la scala specificata.

### Restituisce

Un'immagine contenente il paragrafo renderizzato, o **None**
             se il paragrafo non può essere trovato nella sua raccolta padre, non ha limiti di rendering validi,
             oppure si verifica un errore durante il rendering dell'immagine.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| scale_x | **float** | Il fattore di scala orizzontale applicato all'immagine del paragrafo. |
| scale_y | **float** | Il fattore di scala verticale applicato all'immagine del paragrafo. |



### Vedi anche
* classe [`IImage`](/slides/python-net/it/aspose.slides/iimage)
* classe [`Paragraph`](/slides/python-net/it/aspose.slides/paragraph)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)