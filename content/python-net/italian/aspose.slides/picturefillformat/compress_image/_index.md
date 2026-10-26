---
title: compress_image method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/picturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Comprime l'immagine riducendo le sue dimensioni in base alla dimensione della forma e alla risoluzione specificata. Facoltativamente, elimina anche le aree ritagliate.

### Restituisce

Un **bool** che indica se l'immagine è stata compressa con successo. Restituisce **True** se l'immagine è stata ridimensionata o ritagliata, altrimenti **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Se true, il metodo rimuoverà le aree ritagliate dell'immagine, potenzialmente riducendo ulteriormente le sue dimensioni. |
| resolution | [`PicturesCompression`](/slides/python-net/it/aspose.slides.export/picturescompression) | La risoluzione target per la compressione, specificata come valore dell'enumerazione [`PicturesCompression`](/slides/python-net/it/aspose.slides.export/picturescompression). |

### Osservazioni

Questo metodo cambia le dimensioni e la risoluzione dell'immagine in modo simile alla funzionalità “Picture Format → Compress Pictures” di PowerPoint.

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Generata quando la risoluzione non è un valore valido. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Comprime l'immagine riducendo le sue dimensioni in base alla dimensione della forma e alla risoluzione specificata. Facoltativamente, elimina anche le aree ritagliate.

### Restituisce

Un **bool** che indica se l'immagine è stata compressa con successo. Restituisce **True** se l'immagine è stata ridimensionata o ritagliata, altrimenti **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Se true, il metodo rimuoverà le aree ritagliate dell'immagine, potenzialmente riducendo ulteriormente le sue dimensioni. |
| resolution | **float** | La risoluzione target in DPI. Questo valore deve essere positivo e definisce come l'immagine verrà ridimensionata. |

### Osservazioni

Questo metodo cambia le dimensioni e la risoluzione dell'immagine in modo simile alla funzionalità “Picture Format → Compress Pictures” di PowerPoint.

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Generata quando la risoluzione non è un valore positivo. |



### Vedi anche
* classe [`PictureFillFormat`](/slides/python-net/it/aspose.slides/picturefillformat)
* enumerazione [`PicturesCompression`](/slides/python-net/it/aspose.slides.export/picturescompression)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)