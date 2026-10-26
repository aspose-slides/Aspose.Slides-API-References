---
title: save method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/iimage/save/
weight: 10
---
## save(self, filename) {#str}
Salva l'immagine su un file.


```python
def save(self, filename):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| filename | **str** | Il percorso del file dove verrà salvata l'immagine. |


## save(self, filename, format) {#str-imageformat}
Salva l'immagine in un file nel formato specificato.


```python
def save(self, filename, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| filename | **str** | Il percorso del file dove verrà salvata l'immagine. |
| format | [`ImageFormat`](/slides/python-net/it/aspose.slides/imageformat) | Il formato dell'immagine. |


## save(self, stream, format) {#iorawiobase-imageformat}
Salva l'immagine su uno stream nel formato specificato.


```python
def save(self, stream, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Lo stream in cui l'immagine verrà salvata. |
| format | [`ImageFormat`](/slides/python-net/it/aspose.slides/imageformat) | Il formato dell'immagine. |


## save(self, filename, format, quality) {#str-imageformat-int}
Salva l'immagine in un file nel formato e nella qualità specificati.


```python
def save(self, filename, format, quality):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| filename | **str** | Il percorso del file dove verrà salvata l'immagine. |
| format | [`ImageFormat`](/slides/python-net/it/aspose.slides/imageformat) | Il formato dell'immagine. |
| quality | **int** | La qualità dell'immagine salvata (0 a 100).  <br/><br/>            Questo parametro influisce solo sul salvataggio in [`ImageFormat.JPEG`](/slides/python-net/it/aspose.slides/imageformat/JPEG); per tutti gli altri formati, viene ignorato. |


## save(self, stream, format, quality) {#iorawiobase-imageformat-int}
Salva l'immagine su uno stream nel formato e nella qualità specificati.


```python
def save(self, stream, format, quality):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Lo stream in cui l'immagine verrà salvata. |
| format | [`ImageFormat`](/slides/python-net/it/aspose.slides/imageformat) | Il formato dell'immagine. |
| quality | **int** | La qualità dell'immagine salvata (0 a 100).  <br/><br/>            Questo parametro influisce solo sul salvataggio in [`ImageFormat.JPEG`](/slides/python-net/it/aspose.slides/imageformat/JPEG); per tutti gli altri formati, viene ignorato. |



### Vedi anche
* classe [`IImage`](/slides/python-net/it/aspose.slides/iimage)
* enumerazione [`ImageFormat`](/slides/python-net/it/aspose.slides/imageformat)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)