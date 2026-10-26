---
title: add method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/icaptionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
Aggiunge i sottotitoli chiusi WebVTT alla fine della raccolta.

### Returns

L'istanza [`ICaptions`](/slides/python-net/it/aspose.slides/icaptions) aggiunta.



```python
def add(self, label, file_path):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| label | **str** | L'etichetta dei sottotitoli chiusi. |
| file_path | **str** | Il percorso del file WebVTT. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Lanciata se `file_path` è `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Lanciata se `file_path` è vuoto. |


## add(self, label, stream) {#str-iorawiobase}
Aggiunge i sottotitoli chiusi WebVTT alla fine della raccolta da uno stream.

### Returns

L'istanza [`ICaptions`](/slides/python-net/it/aspose.slides/icaptions) aggiunta.



```python
def add(self, label, stream):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| label | **str** | L'etichetta dei sottotitoli chiusi. |
| stream | **io.RawIOBase** | Lo stream di input contenente dati in formato WebVTT. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Lanciata se `stream` è `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Lanciata se i dati di input non sono nel formato WebVTT. |



### Vedi anche
* classe [`ICaptions`](/slides/python-net/it/aspose.slides/icaptions)
* classe [`ICaptionsCollection`](/slides/python-net/it/aspose.slides/icaptionscollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)