---
title: get_image method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
Restituisce un oggetto Thumbnail Image (20% della dimensione reale).

```python
def get_image(self):
    ...
```

## get_image(self, image_size) {#asposeslidessize}
Restituisce un oggetto Thumbnail Image con la dimensione specificata.

### Restituisce
oggetto Image.

```python
def get_image(self, image_size):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/it/aspose.slides/size) | Dimensione dell'immagine da creare. |

## get_image(self, options) {#asposeslidesexportitiffoptions}
Restituisce un oggetto Thumbnail tiff image con i parametri specificati.

### Restituisce
oggetto Image.

```python
def get_image(self, options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/it/aspose.slides.export/itiffoptions) | Opzioni tiff. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Generato quando options.SlideLayoutOption è NotesCommentsLayoutOptions e la sua proprietà NotesPosition assume il valore NotesPositions.BottomFull. |

## get_image(self, options) {#asposeslidesexportirenderingoptions}
Restituisce un oggetto Thumbnail Image.

### Restituisce
oggetto Image.

```python
def get_image(self, options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/it/aspose.slides.export/irenderingoptions) | Opzioni di rendering. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Generato quando notesCommentsLayouting.NotesPosition assume il valore NotesPositions.BottomFull |

## get_image(self, scale_x, scale_y) {#float-float}
Restituisce un oggetto Thumbnail Image con scalatura personalizzata.

### Restituisce
oggetto IImage.

```python
def get_image(self, scale_x, scale_y):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| scale_x | **float** | Il valore con il quale scalare questo Thumbnail lungo l'asse x. |
| scale_y | **float** | Il valore con il quale scalare questo Thumbnail lungo l'asse y. |

## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Restituisce un oggetto Thumbnail Image con la dimensione specificata.

### Restituisce
oggetto Image.

```python
def get_image(self, options, image_size):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/it/aspose.slides.export/irenderingoptions) | Opzioni di rendering. |
| image_size | [`Size`](/slides/python-net/it/aspose.slides/size) | Dimensione dell'immagine da creare. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Generato quando options.SlideLayoutOption è NotesCommentsLayoutOptions e la sua proprietà NotesPosition assume il valore NotesPositions.BottomFull. |

## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Restituisce un oggetto Thumbnail Image con scalatura personalizzata.

### Restituisce
oggetti Bitmap.

```python
def get_image(self, options, scale_x, scale_y):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/it/aspose.slides.export/irenderingoptions) | Opzioni di rendering. |
| scale_x | **float** | Il valore con il quale scalare questo Thumbnail lungo l'asse x. |
| scale_y | **float** | Il valore con il quale scalare questo Thumbnail lungo l'asse y. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Generato quando notesCommentsLayouting.NotesPosition assume il valore NotesPositions.BottomFull |

### Vedi anche
* classe [`IImage`](/slides/python-net/it/aspose.slides/iimage)
* classe [`IRenderingOptions`](/slides/python-net/it/aspose.slides.export/irenderingoptions)
* classe [`ITiffOptions`](/slides/python-net/it/aspose.slides.export/itiffoptions)
* classe [`Slide`](/slides/python-net/it/aspose.slides/slide)
* classe [`Size`](/slides/python-net/it/aspose.slides/size)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)