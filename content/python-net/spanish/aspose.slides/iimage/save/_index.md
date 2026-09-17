---
title: save method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/iimage/save/
weight: 10
---
## save(self, filename) {#str}
Guarda la imagen en un archivo.


```python
def save(self, filename):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| filename | **str** | La ruta al archivo donde se guardará la imagen. |


## save(self, filename, format) {#str-imageformat}
Guarda la imagen en un archivo en el formato especificado.


```python
def save(self, filename, format):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| filename | **str** | La ruta al archivo donde se guardará la imagen. |
| format | [`ImageFormat`](/slides/python-net/es/aspose.slides/imageformat) | El formato de la imagen. |


## save(self, stream, format) {#iorawiobase-imageformat}
Guarda la imagen en un flujo en el formato especificado.


```python
def save(self, stream, format):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | **io.RawIOBase** | El flujo donde se guardará la imagen. |
| format | [`ImageFormat`](/slides/python-net/es/aspose.slides/imageformat) | El formato de la imagen. |


## save(self, filename, format, quality) {#str-imageformat-int}
Guarda la imagen en un archivo en el formato y calidad especificados.


```python
def save(self, filename, format, quality):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| filename | **str** | La ruta al archivo donde se guardará la imagen. |
| format | [`ImageFormat`](/slides/python-net/es/aspose.slides/imageformat) | El formato de la imagen. |
| quality | **int** | La calidad de la imagen guardada (0 a 100).  <br/><br/>            Este parámetro solo afecta la guardia en [`ImageFormat.JPEG`](/slides/python-net/es/aspose.slides/imageformat/JPEG); para todos los demás formatos, se ignora. |


## save(self, stream, format, quality) {#iorawiobase-imageformat-int}
Guarda la imagen en un flujo en el formato y calidad especificados.


```python
def save(self, stream, format, quality):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | **io.RawIOBase** | El flujo donde se guardará la imagen. |
| format | [`ImageFormat`](/slides/python-net/es/aspose.slides/imageformat) | El formato de la imagen. |
| quality | **int** | La calidad de la imagen guardada (0 a 100).  <br/><br/>            Este parámetro solo afecta la guardia en [`ImageFormat.JPEG`](/slides/python-net/es/aspose.slides/imageformat/JPEG); para todos los demás formatos, se ignora. |



### Ver también
* clase [`IImage`](/slides/python-net/es/aspose.slides/iimage)
* enumeración [`ImageFormat`](/slides/python-net/es/aspose.slides/imageformat)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)