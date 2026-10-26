---
title: add method
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/captionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
Aggiunge i sottotitoli chiusi WebVTT alla fine della raccolta.

### Restituisce

L'istanza [`ICaptions`](/slides/python-net/it/aspose.slides/icaptions) aggiunta.



```python
def add(self, label, file_path):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| label | **str** | L'etichetta dei sottotitoli chiusi. |
| file_path | **str** | Il percorso al file WebVTT. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Lanciata se `file_path` è `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Lanciata se `file_path` è vuoto. |


## add(self, label, stream) {#str-iorawiobase}
Aggiunge i sottotitoli chiusi WebVTT alla fine della raccolta da un flusso.

### Restituisce

L'istanza [`ICaptions`](/slides/python-net/it/aspose.slides/icaptions) aggiunta.



```python
def add(self, label, stream):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| label | **str** | L'etichetta dei sottotitoli chiusi. |
| stream | **io.RawIOBase** | Il flusso di input contenente dati in formato WebVTT. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Lanciata se `stream` è `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Lanciata se i dati in ingresso non sono nel formato WebVTT. |



### Vedi anche
* classe [`CaptionsCollection`](/slides/python-net/it/aspose.slides/captionscollection)
* classe [`ICaptions`](/slides/python-net/it/aspose.slides/icaptions)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)