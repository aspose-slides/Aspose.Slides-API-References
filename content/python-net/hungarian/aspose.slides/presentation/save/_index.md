---
title: save method
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/presentation/save/
weight: 100
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
A prezentáció összes diáját XAML jelölőnyelvet reprezentáló fájlok halmazába menti.


```python
def save(self, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/hu/aspose.slides.export.xaml/ixamloptions) | Az XAML formátum beállításai. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
A prezentáció összes diáját a megadott formátummal egy fájlba menti.


```python
def save(self, fname, format):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| fname | **str** | A létrehozandó fájl elérési útja. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adat formátuma. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
A prezentáció összes diáját a megadott formátumban egy adatfolyamba menti.


```python
def save(self, stream, format):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Kimeneti adatfolyam. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adat formátuma. |


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
A prezentáció összes diáját a megadott formátumban és további beállításokkal egy adatfolyamba menti.


```python
def save(self, stream, format, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Kimeneti adatfolyam. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adat formátuma. |
| options | [`ISaveOptions`](/slides/python-net/hu/aspose.slides.export/isaveoptions) | További formátumbeállítások. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Ha titkosított fájlt próbál menteni a <br/>            nem Office 2007-2010 formátumban. |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
A megadott diákot a prezentációból egy fájlba menti a megadott formátummal, az oldalszámok megtartásával.


```python
def save(self, fname, slides, format):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| fname | **str** | A létrehozandó fájl elérési útja. |
| slides | **List[int]** | Diák pozícióit tartalmazó tömb, 1-től kezdve. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adat formátuma. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Ha a stream vagy a slides paraméter None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Ha a slides paraméter hibás oldalszámokat tartalmaz. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ha nem támogatott SaveFormat van használva, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
A megadott diákot a prezentációból egy adatfolyamba menti a megadott formátummal, az oldalszámok megtartásával.


```python
def save(self, stream, slides, format):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Kimeneti adatfolyam. |
| slides | **List[int]** | Diák pozícióit tartalmazó tömb, 1-től kezdve. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adat formátuma. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
A megadott diákot a prezentációból egy fájlba menti a megadott formátummal, az oldalszámok megtartásával.


```python
def save(self, fname, slides, format, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| fname | **str** | A létrehozandó fájl elérési útja. |
| slides | **List[int]** | Diák pozícióit tartalmazó tömb, 1-től kezdve. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adat formátuma. |
| options | [`ISaveOptions`](/slides/python-net/hu/aspose.slides.export/isaveoptions) | További formátumbeállítások. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
A megadott diákot a prezentációból egy adatfolyamba menti a megadott formátummal, az oldalszámok megtartásával.


```python
def save(self, stream, slides, format, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Kimeneti adatfolyam. |
| slides | **List[int]** | Diák pozícióit tartalmazó tömb, 1-től kezdve. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adat formátuma. |
| options | [`ISaveOptions`](/slides/python-net/hu/aspose.slides.export/isaveoptions) | További formátumbeállítások. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Ha a stream vagy a slides paraméter None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Ha a slides paraméter hibás oldalszámokat tartalmaz. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ha nem támogatott SaveFormat van használva, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### Lásd még
* osztály [`ISaveOptions`](/slides/python-net/hu/aspose.slides.export/isaveoptions)
* osztály [`IXamlOptions`](/slides/python-net/hu/aspose.slides.export.xaml/ixamloptions)
* osztály [`Presentation`](/slides/python-net/hu/aspose.slides/presentation)
* enumeráció [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)