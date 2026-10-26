---
title: save method
second_title: Aspose.Slides dla Pythona poprzez .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/iimage/save/
weight: 10
---
## save(self, filename) {#str}
Zapisuje obraz do pliku.


```python
def save(self, filename):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| filename | **str** | Ścieżka do pliku, w którym zostanie zapisany obraz. |


## save(self, filename, format) {#str-imageformat}
Zapisuje obraz do pliku w określonym formacie.


```python
def save(self, filename, format):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| filename | **str** | Ścieżka do pliku, w którym zostanie zapisany obraz. |
| format | [`ImageFormat`](/slides/python-net/pl/aspose.slides/imageformat) | Format obrazu. |


## save(self, stream, format) {#iorawiobase-imageformat}
Zapisuje obraz do strumienia w określonym formacie.


```python
def save(self, stream, format):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Strumień, w którym zostanie zapisany obraz. |
| format | [`ImageFormat`](/slides/python-net/pl/aspose.slides/imageformat) | Format obrazu. |


## save(self, filename, format, quality) {#str-imageformat-int}
Zapisuje obraz do pliku w określonym formacie i jakości.


```python
def save(self, filename, format, quality):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| filename | **str** | Ścieżka do pliku, w którym zostanie zapisany obraz. |
| format | [`ImageFormat`](/slides/python-net/pl/aspose.slides/imageformat) | Format obrazu. |
| quality | **int** | Jakość zapisanego obrazu (0 do 100).  <br/><br/>            Ten parametr ma wpływ tylko na zapisywanie w [`ImageFormat.JPEG`](/slides/python-net/pl/aspose.slides/imageformat/JPEG); dla wszystkich innych formatów jest ignorowany. |


## save(self, stream, format, quality) {#iorawiobase-imageformat-int}
Zapisuje obraz do strumienia w określonym formacie i jakości.


```python
def save(self, stream, format, quality):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Strumień, w którym zostanie zapisany obraz. |
| format | [`ImageFormat`](/slides/python-net/pl/aspose.slides/imageformat) | Format obrazu. |
| quality | **int** | Jakość zapisanego obrazu (0 do 100).  <br/><br/>            Ten parametr ma wpływ tylko na zapisywanie w [`ImageFormat.JPEG`](/slides/python-net/pl/aspose.slides/imageformat/JPEG); dla wszystkich innych formatów jest ignorowany. |



### Zobacz także
* klasa [`IImage`](/slides/python-net/pl/aspose.slides/iimage)
* enumeracja [`ImageFormat`](/slides/python-net/pl/aspose.slides/imageformat)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)