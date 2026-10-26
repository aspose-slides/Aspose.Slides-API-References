---
title: set_size method
second_title: Aspose.Slides per Python tramite API .NET
description: 
type: docs
url: /it/aspose.slides/islidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Imposta la dimensione della diapositiva per tipo e scala il contenuto esistente.

```python
def set_size(self, type, scale_type):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/it/aspose.slides/slidesizetype) | The predefined slide size to apply. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/it/aspose.slides/slidesizescaletype) | The content scaling mode to use. |

### Osservazioni

L'assegnazione di qualsiasi valore diverso da [`SlideSizeType.CUSTOM`](/slides/python-net/it/aspose.slides/slidesizetype/CUSTOM) regola il [`ISlideSize.size`](/slides/python-net/it/aspose.slides/islidesize/size) in base al tipo selezionato, preservando [`ISlideSize.orientation`](/slides/python-net/it/aspose.slides/islidesize/orientation).

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Imposta le dimensioni della diapositiva esplicitamente e scala il contenuto esistente.

```python
def set_size(self, width, height, scale_type):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| width | **float** | The new slide width, in points. |
| height | **float** | The new slide height, in points. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/it/aspose.slides/slidesizescaletype) | The content scaling mode to use. |

### Osservazioni

Questo reimposta la proprietà [`ISlideSize.type`](/slides/python-net/it/aspose.slides/islidesize/type) a [`SlideSizeType.CUSTOM`](/slides/python-net/it/aspose.slides/slidesizetype/CUSTOM) e imposta il [`ISlideSize.orientation`](/slides/python-net/it/aspose.slides/islidesize/orientation).

### Vedi anche
* classe [`ISlideSize`](/slides/python-net/it/aspose.slides/islidesize)
* enumerazione [`SlideSizeScaleType`](/slides/python-net/it/aspose.slides/slidesizescaletype)
* enumerazione [`SlideSizeType`](/slides/python-net/it/aspose.slides/slidesizetype)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)