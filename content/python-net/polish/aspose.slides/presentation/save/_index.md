---
title: save method
second_title: Aspose.Slides dla Pythona via .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides/presentation/save/
weight: 90
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
| fname | **str** | Ścieżka do utworzonego pliku. |
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

```python
def save(self, fname, format, options):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| fname | **str** |  |
| format | [`SaveFormat`](/slides/python-net/pl/aspose.slides.export/saveformat) |  |
| options | [`ISaveOptions`](/slides/python-net/pl/aspose.slides.export/isaveoptions) |  |

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

| Exception | Opis |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Jeśli spróbujesz zapisać zaszyfrowany plik w <br/>            formacie nieobsługiwanym przez Office 2007-2010 |

## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Zapisuje wybrane slajdy prezentacji do pliku w określonym formacie, zachowując numery stron.

```python
def save(self, fname, slides, format):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| fname | **str** | Ścieżka do utworzonego pliku. |
| slides | **List[int]** | Tablica z pozycjami slajdów, zaczynając od 1. |
| format | [`SaveFormat`](/slides/python-net/pl/aspose.slides.export/saveformat) | Format eksportowanych danych. |

### Wyjątki

| Exception | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Gdy parametr stream lub slides jest None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Gdy parametr slides zawiera nieprawidłowe numery stron. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Gdy użyto nieobsługiwanego SaveFormat, np. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Zapisuje wybrane slajdy prezentacji do strumienia w określonym formacie, zachowując numery stron.

```python
def save(self, stream, slides, format):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Strumień wyjściowy. |
| slides | **List[int]** | Tablica z pozycjami slajdów, zaczynając od 1. |
| format | [`SaveFormat`](/slides/python-net/pl/aspose.slides.export/saveformat) | Format eksportowanych danych. |

## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Zapisuje wybrane slajdy prezentacji do pliku w określonym formacie, zachowując numery stron.

```python
def save(self, fname, slides, format, options):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| fname | **str** | Ścieżka do utworzonego pliku. |
| slides | **List[int]** | Tablica z pozycjami slajdów, zaczynając od 1. |
| format | [`SaveFormat`](/slides/python-net/pl/aspose.slides.export/saveformat) | Format eksportowanych danych. |
| options | [`ISaveOptions`](/slides/python-net/pl/aspose.slides.export/isaveoptions) | Dodatkowe opcje formatu. |

## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Zapisuje wybrane slajdy prezentacji do strumienia w określonym formacie, zachowując numery stron.

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

| Exception | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Gdy parametr stream lub slides jest None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Gdy parametr slides zawiera nieprawidłowe numery stron. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Gdy użyto nieobsługiwanego SaveFormat, np. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Zobacz także
* klasa [`ISaveOptions`](/slides/python-net/pl/aspose.slides.export/isaveoptions)
* klasa [`IXamlOptions`](/slides/python-net/pl/aspose.slides.export.xaml/ixamloptions)
* klasa [`Presentation`](/slides/python-net/pl/aspose.slides/presentation)
* wyliczenie [`SaveFormat`](/slides/python-net/pl/aspose.slides.export/saveformat)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)