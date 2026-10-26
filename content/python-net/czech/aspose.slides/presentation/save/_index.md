---
title: save method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/presentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
Uloží všechny snímky prezentace do sady souborů představujících značkovací jazyk XAML.


```python
def save(self, options):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/cs/aspose.slides.export.xaml/ixamloptions) | Možnosti formátu XAML. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
Uloží všechny snímky prezentace do souboru ve zvoleném formátu.


```python
def save(self, fname, format):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| fname | **str** | Cesta k vytvořenému souboru. |
| format | [`SaveFormat`](/slides/python-net/cs/aspose.slides.export/saveformat) | Formát exportovaných dat. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
Uloží všechny snímky prezentace do proudu ve zvoleném formátu.


```python
def save(self, stream, format):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Výstupní proud. |
| format | [`SaveFormat`](/slides/python-net/cs/aspose.slides.export/saveformat) | Formát exportovaných dat. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}



```python
def save(self, fname, format, options):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| fname | **str** |  |
| format | [`SaveFormat`](/slides/python-net/cs/aspose.slides.export/saveformat) |  |
| options | [`ISaveOptions`](/slides/python-net/cs/aspose.slides.export/isaveoptions) |  |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Uloží všechny snímky prezentace do proudu ve zvoleném formátu a s dalšími možnostmi.


```python
def save(self, stream, format, options):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Výstupní proud. |
| format | [`SaveFormat`](/slides/python-net/cs/aspose.slides.export/saveformat) | Formát exportovaných dat. |
| options | [`ISaveOptions`](/slides/python-net/cs/aspose.slides.export/isaveoptions) | Další možnosti formátu. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | Pokud se pokusíte uložit šifrovaný soubor ve formátu <br/>            none Office 2007-2010 |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
Uloží určené snímky prezentace do souboru ve zvoleném formátu se zachováním čísel stránek.


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
Uloží určené snímky prezentace do proudu ve zvoleném formátu se zachováním čísel stránek.


```python
def save(self, stream, slides, format):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Výstupní proud. |
| slides | **List[int]** | Pole s pozicemi snímků, počínaje 1. |
| format | [`SaveFormat`](/slides/python-net/cs/aspose.slides.export/saveformat) | Formát exportovaných dat. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Uloží určené snímky prezentace do souboru ve zvoleném formátu se zachováním čísel stránek.


```python
def save(self, fname, slides, format, options):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| fname | **str** | Cesta k vytvořenému souboru. |
| slides | **List[int]** | Pole s pozicemi snímků, počínaje 1. |
| format | [`SaveFormat`](/slides/python-net/cs/aspose.slides.export/saveformat) | Formát exportovaných dat. |
| options | [`ISaveOptions`](/slides/python-net/cs/aspose.slides.export/isaveoptions) | Další možnosti formátu. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Uloží určené snímky prezentace do proudu ve zvoleném formátu se zachováním čísel stránek.


```python
def save(self, stream, slides, format, options):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| stream | **io.RawIOBase** | Výstupní proud. |
| slides | **List[int]** | Pole s pozicemi snímků, počínaje 1. |
| format | [`SaveFormat`](/slides/python-net/cs/aspose.slides.export/saveformat) | Formát exportovaných dat. |
| options | [`ISaveOptions`](/slides/python-net/cs/aspose.slides.export/isaveoptions) | Další možnosti formátu. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Když je parametr stream nebo slides nastaven na None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Když parametr slides obsahuje nesprávná čísla stránek. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Když je použit nepodporovaný SaveFormat, např. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### Viz také
* třída [`ISaveOptions`](/slides/python-net/cs/aspose.slides.export/isaveoptions)
* třída [`IXamlOptions`](/slides/python-net/cs/aspose.slides.export.xaml/ixamloptions)
* třída [`Presentation`](/slides/python-net/cs/aspose.slides/presentation)
* enumerace [`SaveFormat`](/slides/python-net/cs/aspose.slides.export/saveformat)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)