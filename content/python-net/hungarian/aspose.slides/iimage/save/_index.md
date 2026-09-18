---
title: save method
second_title: Aspose.Slides Pythonhoz a .NET API hivatkozás segítségével
description: 
type: docs
url: /hu/aspose.slides/iimage/save/
weight: 10
---
## save(self, filename) {#str}
Elmenti a képet egy fájlba.

```python
def save(self, filename):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| filename | **str** | Az a útvonal a fájlhoz, ahová a kép mentésre kerül. |

## save(self, filename, format) {#str-imageformat}
Elmenti a képet egy fájlba a megadott formátumban.

```python
def save(self, filename, format):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| filename | **str** | Az a útvonal a fájlhoz, ahová a kép mentésre kerül. |
| format | [`ImageFormat`](/slides/python-net/hu/aspose.slides/imageformat) | A képek formátuma. |

## save(self, stream, format) {#iorawiobase-imageformat}
Elmenti a képet egy adatfolyamra a megadott formátumban.

```python
def save(self, stream, format):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Az a adatfolyam, ahová a kép mentésre kerül. |
| format | [`ImageFormat`](/slides/python-net/hu/aspose.slides/imageformat) | A képek formátuma. |

## save(self, filename, format, quality) {#str-imageformat-int}
Elmenti a képet egy fájlba a megadott formátumban és minőségben.

```python
def save(self, filename, format, quality):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| filename | **str** | Az a útvonal a fájlhoz, ahová a kép mentésre kerül. |
| format | [`ImageFormat`](/slides/python-net/hu/aspose.slides/imageformat) | A képek formátuma. |
| quality | **int** | A mentett kép minősége (0-tól 100-ig).  <br/><br/>Ez a paraméter csak a [`ImageFormat.JPEG`](/slides/python-net/hu/aspose.slides/imageformat/JPEG) mentésére van hatással; minden más formátúra figyelmen kívül marad. |

## save(self, stream, format, quality) {#iorawiobase-imageformat-int}
Elmenti a képet egy adatfolyamra a megadott formátumban és minőségben.

```python
def save(self, stream, format, quality):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Az a adatfolyam, ahová a kép mentésre kerül. |
| format | [`ImageFormat`](/slides/python-net/hu/aspose.slides/imageformat) | A képek formátuma. |
| quality | **int** | A mentett kép minősége (0-tól 100-ig).  <br/><br/>Ez a paraméter csak a [`ImageFormat.JPEG`](/slides/python-net/hu/aspose.slides/imageformat/JPEG) mentésére van hatással; minden más formátúra figyelmen kívül marad. |

### Lásd még
* osztály [`IImage`](/slides/python-net/hu/aspose.slides/iimage)
* enumeráció [`ImageFormat`](/slides/python-net/hu/aspose.slides/imageformat)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)