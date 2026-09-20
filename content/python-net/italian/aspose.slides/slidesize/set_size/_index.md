---
title: set_size method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/slidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Imposta la dimensione della diapositiva per tipo e ridimensiona il contenuto esistente.

```python
def set_size(self, type, scale_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/it/aspose.slides/slidesizetype) | La dimensione della diapositiva predefinita da applicare. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/it/aspose.slides/slidesizescaletype) | La modalità di scala del contenuto da utilizzare. |

### Osservazioni

Assegnare qualsiasi valore diverso da [`SlideSizeType.CUSTOM`](/slides/python-net/it/aspose.slides/slidesizetype/CUSTOM) regola il [`SlideSize.size`](/slides/python-net/it/aspose.slides/slidesize/size) in base al tipo selezionato, mantenendo [`SlideSize.orientation`](/slides/python-net/it/aspose.slides/slidesize/orientation).

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Imposta esplicitamente le dimensioni della diapositiva e ridimensiona il contenuto esistente.

```python
def set_size(self, width, height, scale_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| width | **float** | La nuova larghezza della diapositiva, in punti. |
| height | **float** | La nuova altezza della diapositiva, in punti. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/it/aspose.slides/slidesizescaletype) | La modalità di scala del contenuto da utilizzare. |

### Osservazioni

Questo ripristina la proprietà [`SlideSize.type`](/slides/python-net/it/aspose.slides/slidesize/type) a [`SlideSizeType.CUSTOM`](/slides/python-net/it/aspose.slides/slidesizetype/CUSTOM) e imposta il [`SlideSize.orientation`](/slides/python-net/it/aspose.slides/slidesize/orientation).

### Vedi anche
* classe [`SlideSize`](/slides/python-net/it/aspose.slides/slidesize)
* enumerazione [`SlideSizeScaleType`](/slides/python-net/it/aspose.slides/slidesizescaletype)
* enumerazione [`SlideSizeType`](/slides/python-net/it/aspose.slides/slidesizetype)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)