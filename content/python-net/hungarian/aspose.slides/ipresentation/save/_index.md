---
title: save method
second_title: Aspose.Slides for Python via .NET API Referenciája
description: 
type: docs
url: /hu/aspose.slides/ipresentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Ment minden diát egy prezentációból egy sor fájlba, amely XAML jelölőnyelvet tartalmaz.


```python
def save(self, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/hu/aspose.slides.export.xaml/ixamloptions) | A XAML formátum opciói. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Ment minden diát egy prezentációból egy fájlba a megadott formátummal.


```python
def save(self, fname, format):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| fname | **str** | Az elkészített fájl elérési útja. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adatok formátuma. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Ment minden diát egy prezentációból egy adatfolyamba a megadott formátummal.


```python
def save(self, stream, format):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Kimeneti adatfolyam. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adatok formátuma. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Ment minden diát egy prezentációból egy fájlba a megadott formátummal és további opciókkal.


```python
def save(self, fname, format, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| fname | **str** | Az elkészített fájl elérési útja. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adatok formátuma. |
| options | [`ISaveOptions`](/slides/python-net/hu/aspose.slides.export/isaveoptions) | További formátumopciók. |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Ment minden diát egy prezentációból egy adatfolyamba a megadott formátummal és további opciókkal.


```python
def save(self, stream, format, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Kimeneti adatfolyam. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adatok formátuma. |
| options | [`ISaveOptions`](/slides/python-net/hu/aspose.slides.export/isaveoptions) | További formátumopciók. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Ha megpróbál titkosított fájlt menteni egy <br/>            nem Office 2007-2010 formátumban |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Ment egy prezentáció megadott diáit egy fájlba a megadott formátummal.


```python
def save(self, fname, slides, format):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| fname | **str** | Az elkészített fájl elérési útja. |
| slides | **List[int]** | Tömb a dia pozícióival, 1-től kezdve. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adatok formátuma. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Ha a stream vagy a slides paraméter None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Ha a slides paraméter helytelen oldalszámokat tartalmaz. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ha egy nem támogatott SaveFormat kerül használatra, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Ment egy prezentáció megadott diáit egy adatfolyamba a megadott formátummal.


```python
def save(self, stream, slides, format):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Kimeneti adatfolyam. |
| slides | **List[int]** | Tömb a dia pozícióival, 1-től kezdve. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adatok formátuma. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Ha a stream vagy a slides paraméter None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Ha a slides paraméter helytelen oldalszámokat tartalmaz. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ha egy nem támogatott SaveFormat kerül használatra, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Ment egy prezentáció megadott diáit egy fájlba a megadott formátummal.


```python
def save(self, fname, slides, format, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| fname | **str** | Az elkészített fájl elérési útja. |
| slides | **List[int]** | Tömb a dia pozícióival, 1-től kezdve. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adatok formátuma. |
| options | [`ISaveOptions`](/slides/python-net/hu/aspose.slides.export/isaveoptions) | További formátumopciók. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Ha a stream vagy a slides paraméter None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Ha a slides paraméter helytelen oldalszámokat tartalmaz. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ha egy nem támogatott SaveFormat kerül használatra, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Ment egy prezentáció megadott diáit egy adatfolyamba a megadott formátummal.


```python
def save(self, stream, slides, format, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Kimeneti adatfolyam. |
| slides | **List[int]** | Tömb a dia pozícióival, 1-től kezdve. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adatok formátuma. |
| options | [`ISaveOptions`](/slides/python-net/hu/aspose.slides.export/isaveoptions) | További formátumopciók. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Ha a stream vagy a slides paraméter None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Ha a slides paraméter helytelen oldalszámokat tartalmaz. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ha egy nem támogatott SaveFormat kerül használatra, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### Lásd még
* osztály [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation)
* osztály [`ISaveOptions`](/slides/python-net/hu/aspose.slides.export/isaveoptions)
* osztály [`IXamlOptions`](/slides/python-net/hu/aspose.slides.export.xaml/ixamloptions)
* enumeráció [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)