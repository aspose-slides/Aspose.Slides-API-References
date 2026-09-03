---
title: get_image method
second_title: Aspose.Slides per Python via .NET API Reference
description: 
type: docs
url: /it/aspose.slides/iparagraph/get_image/
weight: 10
---
## get_image {#}
Restituisce un'immagine del paragrafo.

### Restituisce

Un'immagine contenente il paragrafo renderizzato, o **None**
 se il paragrafo non può essere trovato nella sua collezione genitore, non ha limiti di rendering validi,
 o si verifica un errore durante il rendering dell'immagine.



```python
def get_image(self):
    ...
```



## get_image {#float-float}
Restituisce un'immagine del paragrafo con la scala specificata.

### Restituisce

Un'immagine contenente il paragrafo renderizzato, o **None**
 se il paragrafo non può essere trovato nella sua collezione genitore, non ha limiti di rendering validi,
 o si verifica un errore durante il rendering dell'immagine.



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
* classe [`IParagraph`](/slides/python-net/it/aspose.slides/iparagraph)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)