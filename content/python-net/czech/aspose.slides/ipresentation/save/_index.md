---
title: save method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ipresentation/save/
weight: 80
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Uloží všechny snímky prezentace do sady souborů představujících značkování XAML.

```python
def save(self, options):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/cs/aspose.slides.export.xaml/ixamloptions) | Možnosti formátu XAML. |

## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Uloží všechny snímky prezentace do souboru ve specifikovaném formátu.

```python
def save(self, fname, format):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| fname | **str** | Cesta k vytvořenému souboru. |
| format | [`SaveFormat`](/slides/python-net/cs/aspose.slides.export/saveformat) | Formát exportovaných dat. |

## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Uloží všechny snímky prezentace do proudu ve specifikovaném formátu.

```python
def save(self, stream, format):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Výstupní proud. |
| format | [`SaveFormat`](/slides/python-net/cs/aspose.slides.export/saveformat) | Formát exportovaných dat. |

## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Uloží všechny snímky prezentace do souboru ve specifikovaném formátu s dodatečnými možnostmi.

```python
def save(self, fname, format, options):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| fname | **str** | Cesta k vytvořenému souboru. |
| format | [`SaveFormat`](/slides/python-net/cs/aspose.slides.export/saveformat) | Formát exportovaných dat. |
| options | [`ISaveOptions`](/slides/python-net/cs/aspose.slides.export/isaveoptions) | Dodatečné možnosti formátu. |

## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Uloží všechny snímky prezentace do proudu ve specifikovaném formátu s dodatečnými možnostmi.

```python
def save(self, stream, format, options):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Výstupní proud. |
| format | [`SaveFormat`](/slides/python-net/cs/aspose.slides.export/saveformat) | Formát exportovaných dat. |
| options | [`ISaveOptions`](/slides/python-net/cs/aspose.slides.export/isaveoptions) | Dodatečné možnosti formátu. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Pokud se pokusíte uložit šifrovaný soubor v <br/>            žádném formátu Office 2007-2010 |

## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Uloží určené snímky prezentace do souboru ve specifikovaném formátu.

```python
def save(self, fname, slides, format):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| fname | **str** | Cesta k vytvořenému souboru. |
| slides | **List[int]** | Pole s pozicemi snímků, počínaje 1. |
| format | [`SaveFormat`](/slides/python-net/cs/aspose.slides.export/saveformat) | Formát exportovaných dat. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Když je parametr stream nebo slides nastaven na None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Když parametr slides obsahuje nesprávná čísla stránek. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Když je použit nepodporovaný SaveFormat, např. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
Uloží určené snímky prezentace do proudu ve specifikovaném formátu.

```python
def save(self, stream, slides, format):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Výstupní proud. |
| slides | **List[int]** | Pole s pozicemi snímků, počínaje 1. |
| format | [`SaveFormat`](/slides/python-net/cs/aspose.slides.export/saveformat) | Formát exportovaných dat. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Když je parametr stream nebo slides nastaven na None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Když parametr slides obsahuje nesprávná čísla stránek. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Když je použit nepodporovaný SaveFormat, např. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Uloží určené snímky prezentace do souboru ve specifikovaném formátu.

```python
def save(self, fname, slides, format, options):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| fname | **str** | Cesta k vytvořenému souboru. |
| slides | **List[int]** | Pole s pozicemi snímků, počínaje 1. |
| format | [`SaveFormat`](/slides/python-net/cs/aspose.slides.export/saveformat) | Formát exportovaných dat. |
| options | [`ISaveOptions`](/slides/python-net/cs/aspose.slides.export/isaveoptions) | Dodatečné možnosti formátu. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Když je parametr stream nebo slides nastaven na None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Když parametr slides obsahuje nesprávná čísla stránek. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Když je použit nepodporovaný SaveFormat, např. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Uloží určené snímky prezentace do proudu ve specifikovaném formátu.

```python
def save(self, stream, slides, format, options):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Výstupní proud. |
| slides | **List[int]** | Pole s pozicemi snímků, počínaje 1. |
| format | [`SaveFormat`](/slides/python-net/cs/aspose.slides.export/saveformat) | Formát exportovaných dat. |
| options | [`ISaveOptions`](/slides/python-net/cs/aspose.slides.export/isaveoptions) | Dodatečné možnosti formátu. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Když je parametr stream nebo slides nastaven na None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Když parametr slides obsahuje nesprávná čísla stránek. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Když je použit nepodporovaný SaveFormat, např. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Viz také
* třída [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation)
* třída [`ISaveOptions`](/slides/python-net/cs/aspose.slides.export/isaveoptions)
* třída [`IXamlOptions`](/slides/python-net/cs/aspose.slides.export.xaml/ixamloptions)
* výčet [`SaveFormat`](/slides/python-net/cs/aspose.slides.export/saveformat)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)