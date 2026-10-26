---
title: save method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/iimage/save/
weight: 10
---
## save(self, filename) {#str}
Sparar bilden till en fil.


```python
def save(self, filename):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| filename | **str** | Sökvägen till filen där bilden kommer att sparas. |


## save(self, filename, format) {#str-imageformat}
Sparar bilden till en fil i det angivna formatet.


```python
def save(self, filename, format):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| filename | **str** | Sökvägen till filen där bilden kommer att sparas. |
| format | [`ImageFormat`](/slides/python-net/sv/aspose.slides/imageformat) | Bildformatet. |


## save(self, stream, format) {#iorawiobase-imageformat}
Sparar bilden till en ström i det angivna formatet.


```python
def save(self, stream, format):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | **io.RawIOBase** | Strömmen där bilden kommer att sparas. |
| format | [`ImageFormat`](/slides/python-net/sv/aspose.slides/imageformat) | Bildformatet. |


## save(self, filename, format, quality) {#str-imageformat-int}
Sparar bilden till en fil i det angivna formatet och kvaliteten.


```python
def save(self, filename, format, quality):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| filename | **str** | Sökvägen till filen där bilden kommer att sparas. |
| format | [`ImageFormat`](/slides/python-net/sv/aspose.slides/imageformat) | Bildformatet. |
| quality | **int** | Den sparade bildens kvalitet (0 till 100).  <br/><br/>            Denna parameter påverkar endast sparande i [`ImageFormat.JPEG`](/slides/python-net/sv/aspose.slides/imageformat/JPEG); för alla andra format ignoreras den. |


## save(self, stream, format, quality) {#iorawiobase-imageformat-int}
Sparar bilden till en ström i det angivna formatet och kvaliteten.


```python
def save(self, stream, format, quality):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | **io.RawIOBase** | Strömmen där bilden kommer att sparas. |
| format | [`ImageFormat`](/slides/python-net/sv/aspose.slides/imageformat) | Bildformatet. |
| quality | **int** | Den sparade bildens kvalitet (0 till 100).  <br/><br/>            Denna parameter påverkar endast sparande i [`ImageFormat.JPEG`](/slides/python-net/sv/aspose.slides/imageformat/JPEG); för alla andra format ignoreras den. |



### Se även
* klass [`IImage`](/slides/python-net/sv/aspose.slides/iimage)
* enumeration [`ImageFormat`](/slides/python-net/sv/aspose.slides/imageformat)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)