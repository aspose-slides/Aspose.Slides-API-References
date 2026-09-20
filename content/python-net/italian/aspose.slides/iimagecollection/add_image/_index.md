---
title: add_image method
second_title: Aspose.Slides per Python tramite API di riferimento .NET
description: 
type: docs
url: /it/aspose.slides/iimagecollection/add_image/
weight: 10
---
## add_image(self, image) {#iimage}
Aggiungi un'immagine a una presentazione.

### Restituisce

Immagine aggiunta.



```python
def add_image(self, image):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/it/aspose.slides/iimage) | Immagine da aggiungere. |

### Osservazioni

Questo metodo converte i metafili WMF/EMF in immagini PNG raster prima di inserirli in una presentazione.


## add_image(self, stream) {#iorawiobase}
Aggiungi un'immagine a una presentazione da flusso.

### Restituisce

Immagine aggiunta.



```python
def add_image(self, stream):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flusso da cui aggiungere l'immagine. |

### Osservazioni

Questo metodo può aggiungere i metafili WMF/EMF a una presentazione senza convertirli in immagine PNG raster.


## add_image(self, buffer) {#bytes}
Aggiunge un'immagine a una presentazione dal buffer specificato.

### Restituisce

Immagine aggiunta.



```python
def add_image(self, buffer):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| buffer | **bytes** | Buffer. |


## add_image(self, image_source) {#ippimage}
Aggiunge una copia di un'immagine da un'altra presentazione.

### Restituisce

Immagine aggiunta.



```python
def add_image(self, image_source):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage) | Immagine sorgente. |


## add_image(self, svg_image) {#isvgimage}
Aggiungi un'immagine a una presentazione da oggetto SVG.

### Restituisce

Immagine aggiunta.



```python
def add_image(self, svg_image):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/it/aspose.slides/isvgimage) | Oggetto immagine SVG [`ISvgImage`](/slides/python-net/it/aspose.slides/isvgimage) |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Generata quando il parametro svgImage è None. |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Crea e aggiunge un'immagine a una presentazione da flusso.

### Restituisce

Aggiunto [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage).



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | **io.RawIOBase** | Flusso da cui aggiungere il file immagine. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/it/aspose.slides/loadingstreambehavior) | Il comportamento che sarà applicato al flusso. |



### Vedi anche
* classe [`IImage`](/slides/python-net/it/aspose.slides/iimage)
* classe [`IImageCollection`](/slides/python-net/it/aspose.slides/iimagecollection)
* classe [`IPPImage`](/slides/python-net/it/aspose.slides/ippimage)
* classe [`ISvgImage`](/slides/python-net/it/aspose.slides/isvgimage)
* enumerazione [`LoadingStreamBehavior`](/slides/python-net/it/aspose.slides/loadingstreambehavior)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)