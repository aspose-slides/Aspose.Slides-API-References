---
title: save method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/iimage/save/
weight: 10
---
## save(self, filename) {#str}
Speichert das Bild in einer Datei.


```python
def save(self, filename):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| filename | **str** | Der Pfad zu der Datei, in der das Bild gespeichert wird. |


## save(self, filename, format) {#str-imageformat}
Speichert das Bild in einer Datei im angegebenen Format.


```python
def save(self, filename, format):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| filename | **str** | Der Pfad zu der Datei, in der das Bild gespeichert wird. |
| format | [`ImageFormat`](/slides/python-net/de/aspose.slides/imageformat) | Das Bildformat. |


## save(self, stream, format) {#iorawiobase-imageformat}
Speichert das Bild in einem Stream im angegebenen Format.


```python
def save(self, stream, format):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | **io.RawIOBase** | Der Stream, in dem das Bild gespeichert wird. |
| format | [`ImageFormat`](/slides/python-net/de/aspose.slides/imageformat) | Das Bildformat. |


## save(self, filename, format, quality) {#str-imageformat-int}
Speichert das Bild in einer Datei im angegebenen Format und mit angegebenen Qualität.


```python
def save(self, filename, format, quality):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| filename | **str** | Der Pfad zu der Datei, in der das Bild gespeichert wird. |
| format | [`ImageFormat`](/slides/python-net/de/aspose.slides/imageformat) | Das Bildformat. |
| quality | **int** | Die Qualität des gespeicherten Bildes (0 bis 100).  <br/><br/>            Dieser Parameter wirkt sich nur auf das Speichern in [`ImageFormat.JPEG`](/slides/python-net/de/aspose.slides/imageformat/JPEG) aus; für alle anderen Formate wird er ignoriert. |


## save(self, stream, format, quality) {#iorawiobase-imageformat-int}
Speichert das Bild in einem Stream im angegebenen Format und mit angegebenen Qualität.


```python
def save(self, stream, format, quality):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | **io.RawIOBase** | Der Stream, in dem das Bild gespeichert wird. |
| format | [`ImageFormat`](/slides/python-net/de/aspose.slides/imageformat) | Das Bildformat. |
| quality | **int** | Die Qualität des gespeicherten Bildes (0 bis 100).  <br/><br/>            Dieser Parameter wirkt sich nur auf das Speichern in [`ImageFormat.JPEG`](/slides/python-net/de/aspose.slides/imageformat/JPEG) aus; für alle anderen Formate wird er ignoriert. |



### Siehe Auch
* Klasse [`IImage`](/slides/python-net/de/aspose.slides/iimage)
* Aufzählung [`ImageFormat`](/slides/python-net/de/aspose.slides/imageformat)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)