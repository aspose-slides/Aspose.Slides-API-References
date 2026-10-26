---
title: save method
second_title: Aspose.Slides Pythonhoz a .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides/presentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Ment minden diát egy prezentációból egy sor fájlba, amely XAML jelölőnyelvet képvisel.


```python
def save(self, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/hu/aspose.slides.export.xaml/ixamloptions) | A XAML formátum beállításai. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Ment minden diát egy prezentációból egy megadott formátumú fájlba.


```python
def save(self, fname, format):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| fname | **str** | Az elkészített fájl elérési útja. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adatok formátuma. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Ment minden diát egy prezentációból egy adatfolyamra a megadott formátumban.


```python
def save(self, stream, format):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Kimeneti adatfolyam. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adatok formátuma. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}


```python
def save(self, fname, format, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| fname | **str** |  |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) |  |
| options | [`ISaveOptions`](/slides/python-net/hu/aspose.slides.export/isaveoptions) |  |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Ment minden diát egy prezentációból egy adatfolyamra a megadott formátumban és további beállításokkal.


```python
def save(self, stream, format, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Kimeneti adatfolyam. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adatok formátuma. |
| options | [`ISaveOptions`](/slides/python-net/hu/aspose.slides.export/isaveoptions) | További formátumbeállítások. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Ha megpróbál titkosított fájlt menteni egy nem Office 2007-2010 formátumba. |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Ment egy prezentáció megadott diáit egy fájlba a megadott formátummal, megtartva az oldalszámot.


```python
def save(self, fname, slides, format):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| fname | **str** | Az elkészített fájl elérési útja. |
| slides | **List[int]** | A diák pozícióit (1-től) tartalmazó tömb. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adatok formátuma. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Ha a stream vagy slides paraméter None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Ha a slides paraméter hibás oldal számokat tartalmaz. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ha nem támogatott SaveFormat kerül felhasználásra, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Ment egy prezentáció megadott diáit egy adatfolyamra a megadott formátumban, megtartva az oldalszámot.


```python
def save(self, stream, slides, format):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Kimeneti adatfolyam. |
| slides | **List[int]** | A diák pozícióit (1-től) tartalmazó tömb. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adatok formátuma. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Ment egy prezentáció megadott diáit egy fájlba a megadott formátummal, megtartva az oldalszámot.


```python
def save(self, fname, slides, format, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| fname | **str** | Az elkészített fájl elérési útja. |
| slides | **List[int]** | A diák pozícióit (1-től) tartalmazó tömb. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adatok formátuma. |
| options | [`ISaveOptions`](/slides/python-net/hu/aspose.slides.export/isaveoptions) | További formátumbeállítások. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Ment egy prezentáció megadott diáit egy adatfolyamra a megadott formátumban, megtartva az oldalszámot.


```python
def save(self, stream, slides, format, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Kimeneti adatfolyam. |
| slides | **List[int]** | A diák pozícióit (1-től) tartalmazó tömb. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adatok formátuma. |
| options | [`ISaveOptions`](/slides/python-net/hu/aspose.slides.export/isaveoptions) | További formátumbeállítások. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Ha a stream vagy slides paraméter None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Ha a slides paraméter hibás oldal számokat tartalmaz. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ha nem támogatott SaveFormat kerül felhasználásra, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### Lásd még
* osztály [`ISaveOptions`](/slides/python-net/hu/aspose.slides.export/isaveoptions)
* osztály [`IXamlOptions`](/slides/python-net/hu/aspose.slides.export.xaml/ixamloptions)
* osztály [`Presentation`](/slides/python-net/hu/aspose.slides/presentation)
* enumeráció [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)