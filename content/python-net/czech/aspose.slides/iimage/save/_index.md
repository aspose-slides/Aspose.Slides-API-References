---
title: save method
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/iimage/save/
weight: 10
---
## save(self, filename) {#str}
Uloží obrázek do souboru.


```python
def save(self, filename):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| filename | **str** | Cesta k souboru, do kterého bude obrázek uložen. |


## save(self, filename, format) {#str-imageformat}
Uloží obrázek do souboru ve zvoleném formátu.


```python
def save(self, filename, format):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| filename | **str** | Cesta k souboru, do kterého bude obrázek uložen. |
| format | [`ImageFormat`](/slides/python-net/cs/aspose.slides/imageformat) | Formát obrázku. |


## save(self, stream, format) {#iorawiobase-imageformat}
Uloží obrázek do proudu ve zvoleném formátu.


```python
def save(self, stream, format):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Proud, do kterého bude obrázek uložen. |
| format | [`ImageFormat`](/slides/python-net/cs/aspose.slides/imageformat) | Formát obrázku. |


## save(self, filename, format, quality) {#str-imageformat-int}
Uloží obrázek do souboru ve zvoleném formátu a kvalitě.


```python
def save(self, filename, format, quality):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| filename | **str** | Cesta k souboru, do kterého bude obrázek uložen. |
| format | [`ImageFormat`](/slides/python-net/cs/aspose.slides/imageformat) | Formát obrázku. |
| quality | **int** | Kvalita uloženého obrázku (0 až 100).  <br/><br/>            Tento parametr ovlivňuje ukládání pouze v [`ImageFormat.JPEG`](/slides/python-net/cs/aspose.slides/imageformat/JPEG); pro všechny ostatní formáty je ignorován. |


## save(self, stream, format, quality) {#iorawiobase-imageformat-int}
Uloží obrázek do proudu ve zvoleném formátu a kvalitě.


```python
def save(self, stream, format, quality):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Proud, do kterého bude obrázek uložen. |
| format | [`ImageFormat`](/slides/python-net/cs/aspose.slides/imageformat) | Formát obrázku. |
| quality | **int** | Kvalita uloženého obrázku (0 až 100).  <br/><br/>            Tento parametr ovlivňuje ukládání pouze v [`ImageFormat.JPEG`](/slides/python-net/cs/aspose.slides/imageformat/JPEG); pro všechny ostatní formáty je ignorován. |



### Viz také
* class [`IImage`](/slides/python-net/cs/aspose.slides/iimage)
* enumeration [`ImageFormat`](/slides/python-net/cs/aspose.slides/imageformat)
* module [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)