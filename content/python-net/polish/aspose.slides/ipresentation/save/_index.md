---
title: save method
second_title: Aspose.Slides dla Pythona przy użyciu .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides/ipresentation/save/
weight: 80
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Zapisuje wszystkie slajdy prezentacji do zestawu plików reprezentujących znacznik XAML.


```python
def save(self, options):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/pl/aspose.slides.export.xaml/ixamloptions) | Opcje formatu XAML. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie.


```python
def save(self, fname, format):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| fname | **str** | Ścieżka do tworzonego pliku. |
| format | [`SaveFormat`](/slides/python-net/pl/aspose.slides.export/saveformat) | Format eksportowanych danych. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Zapisuje wszystkie slajdy prezentacji do strumienia w określonym formacie.


```python
def save(self, stream, format):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Strumień wyjściowy. |
| format | [`SaveFormat`](/slides/python-net/pl/aspose.slides.export/saveformat) | Format eksportowanych danych. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie oraz z dodatkowymi opcjami.


```python
def save(self, fname, format, options):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| fname | **str** | Ścieżka do tworzonego pliku. |
| format | [`SaveFormat`](/slides/python-net/pl/aspose.slides.export/saveformat) | Format eksportowanych danych. |
| options | [`ISaveOptions`](/slides/python-net/pl/aspose.slides.export/isaveoptions) | Dodatkowe opcje formatu. |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Zapisuje wszystkie slajdy prezentacji do strumienia w określonym formacie oraz z dodatkowymi opcjami.


```python
def save(self, stream, format, options):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Strumień wyjściowy. |
| format | [`SaveFormat`](/slides/python-net/pl/aspose.slides.export/saveformat) | Format eksportowanych danych. |
| options | [`ISaveOptions`](/slides/python-net/pl/aspose.slides.export/isaveoptions) | Dodatkowe opcje formatu. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Jeśli spróbujesz zapisać zaszyfrowany plik w <br/>            formacie innym niż Office 2007-2010 |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Zapisuje określone slajdy prezentacji do pliku w określonym formacie.


```python
def save(self, fname, slides, format):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| fname | **str** | Ścieżka do tworzonego pliku. |
| slides | **List[int]** | Tablica z pozycjami slajdów, zaczynając od 1. |
| format | [`SaveFormat`](/slides/python-net/pl/aspose.slides.export/saveformat) | Format eksportowanych danych. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Gdy parametr stream lub slides ma wartość None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Gdy parametr slides zawiera nieprawidłowe numery stron. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Gdy użyto nieobsługiwanego SaveFormat, np. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Zapisuje określone slajdy prezentacji do strumienia w określonym formacie.


```python
def save(self, stream, slides, format):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Strumień wyjściowy. |
| slides | **List[int]** | Tablica z pozycjami slajdów, zaczynając od 1. |
| format | [`SaveFormat`](/slides/python-net/pl/aspose.slides.export/saveformat) | Format eksportowanych danych. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Gdy parametr stream lub slides ma wartość None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Gdy parametr slides zawiera nieprawidłowe numery stron. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Gdy użyto nieobsługiwanego SaveFormat, np. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Zapisuje określone slajdy prezentacji do pliku w określonym formacie.


```python
def save(self, fname, slides, format, options):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| fname | **str** | Ścieżka do tworzonego pliku. |
| slides | **List[int]** | Tablica z pozycjami slajdów, zaczynając od 1. |
| format | [`SaveFormat`](/slides/python-net/pl/aspose.slides.export/saveformat) | Format eksportowanych danych. |
| options | [`ISaveOptions`](/slides/python-net/pl/aspose.slides.export/isaveoptions) | Dodatkowe opcje formatu. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Gdy parametr stream lub slides ma wartość None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Gdy parametr slides zawiera nieprawidłowe numery stron. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Gdy użyto nieobsługiwanego SaveFormat, np. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Zapisuje określone slajdy prezentacji do strumienia w określonym formacie.


```python
def save(self, stream, slides, format, options):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Strumień wyjściowy. |
| slides | **List[int]** | Tablica z pozycjami slajdów, zaczynając od 1. |
| format | [`SaveFormat`](/slides/python-net/pl/aspose.slides.export/saveformat) | Format eksportowanych danych. |
| options | [`ISaveOptions`](/slides/python-net/pl/aspose.slides.export/isaveoptions) | Dodatkowe opcje formatu. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Gdy parametr stream lub slides ma wartość None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Gdy parametr slides zawiera nieprawidłowe numery stron. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Gdy użyto nieobsługiwanego SaveFormat, np. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### Zobacz także
* klasa [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation)
* klasa [`ISaveOptions`](/slides/python-net/pl/aspose.slides.export/isaveoptions)
* klasa [`IXamlOptions`](/slides/python-net/pl/aspose.slides.export.xaml/ixamloptions)
* enumeracja [`SaveFormat`](/slides/python-net/pl/aspose.slides.export/saveformat)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)