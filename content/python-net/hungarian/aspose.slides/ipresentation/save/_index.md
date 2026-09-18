---
title: save method
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/ipresentation/save/
weight: 80
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Elmenti egy prezentáció összes diáját egy XAML jelölőnyelvet reprezentáló fájlkészletbe.


```python
def save(self, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/hu/aspose.slides.export.xaml/ixamloptions) | A XAML formátum beállításai. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Elmenti egy prezentáció összes diáját egy megadott formátumú fájlba.


```python
def save(self, fname, format):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| fname | **str** | Az elkészített fájl elérési útja. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adatok formátuma. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Elmenti egy prezentáció összes diáját egy megadott formátumú adatfolyamba.


```python
def save(self, stream, format):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Kimeneti adatfolyam. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adatok formátuma. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Elmenti egy prezentáció összes diáját egy megadott formátumú fájlba további beállításokkal.


```python
def save(self, fname, format, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| fname | **str** | Az elkészített fájl elérési útja. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adatok formátuma. |
| options | [`ISaveOptions`](/slides/python-net/hu/aspose.slides.export/isaveoptions) | További formátum beállítások. |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Elmenti egy prezentáció összes diáját egy megadott formátumú adatfolyamba további beállításokkal.


```python
def save(self, stream, format, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Kimeneti adatfolyam. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adatok formátuma. |
| options | [`ISaveOptions`](/slides/python-net/hu/aspose.slides.export/isaveoptions) | További formátum beállítások. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Ha megpróbál titkosított fájlt elmenteni <br/>            nem Office 2007-2010 formátumban. |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Elmenti egy prezentáció megadott diáit egy megadott formátumú fájlba.


```python
def save(self, fname, slides, format):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| fname | **str** | Az elkészített fájl elérési útja. |
| slides | **List[int]** | Az diápozíciók tömbje, 1-től kezdve. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adatok formátuma. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Ha a stream vagy a slides paraméter None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Ha a slides paraméter helytelen oldal számokat tartalmaz. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ha nem támogatott SaveFormat-ot használnak, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Elmenti egy prezentáció megadott diáit egy megadott formátumú adatfolyamba.


```python
def save(self, stream, slides, format):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Kimeneti adatfolyam. |
| slides | **List[int]** | Az diápozíciók tömbje, 1-től kezdve. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adatok formátuma. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Ha a stream vagy a slides paraméter None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Ha a slides paraméter helytelen oldal számokat tartalmaz. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ha nem támogatott SaveFormat-ot használnak, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Elmenti egy prezentáció megadott diáit egy megadott formátumú fájlba.


```python
def save(self, fname, slides, format, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| fname | **str** | Az elkészített fájl elérési útja. |
| slides | **List[int]** | Az diápozíciók tömbje, 1-től kezdve. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adatok formátuma. |
| options | [`ISaveOptions`](/slides/python-net/hu/aspose.slides.export/isaveoptions) | További formátum beállítások. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Ha a stream vagy a slides paraméter None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Ha a slides paraméter helytelen oldal számokat tartalmaz. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ha nem támogatott SaveFormat-ot használnak, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Elmenti egy prezentáció megadott diáit egy megadott formátumú adatfolyamba.


```python
def save(self, stream, slides, format, options):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Kimeneti adatfolyam. |
| slides | **List[int]** | Az diápozíciók tömbje, 1-től kezdve. |
| format | [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat) | Az exportált adatok formátuma. |
| options | [`ISaveOptions`](/slides/python-net/hu/aspose.slides.export/isaveoptions) | További formátum beállítások. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Ha a stream vagy a slides paraméter None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Ha a slides paraméter helytelen oldal számokat tartalmaz. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ha nem támogatott SaveFormat-ot használnak, például PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### Lásd még
* osztály [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation)
* osztály [`ISaveOptions`](/slides/python-net/hu/aspose.slides.export/isaveoptions)
* osztály [`IXamlOptions`](/slides/python-net/hu/aspose.slides.export.xaml/ixamloptions)
* enumeráció [`SaveFormat`](/slides/python-net/hu/aspose.slides.export/saveformat)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)