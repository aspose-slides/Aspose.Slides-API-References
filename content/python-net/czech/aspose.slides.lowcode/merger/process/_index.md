---
title: process method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.lowcode/merger/process/
weight: 10
---
## process(input_file_names, output_file_name) {#liststr-str}
Sloučí více prezentací PowerPoint ve stejném formátu do jediného souboru prezentace.

```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| input_file_names | **List[str]** | Pole názvů vstupních souborů prezentací. |
| output_file_name | **str** | Název výstupního souboru výsledné sloučené prezentace. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, když jsou názvy vstupních souborů neplatné nebo se formáty neshodují. |

## process(input_file_names, output_stream) {#liststr-iorawiobase}
Sloučí více prezentací PowerPoint ve stejném formátu do jediného souboru prezentace.

```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| input_file_names | **List[str]** | Pole názvů vstupních souborů prezentací. |
| output_stream | **io.RawIOBase** | Výstupní proud. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, když jsou názvy vstupních souborů neplatné nebo se formáty neshodují. |

## process(input_file_names, output_file_name, options) {#liststr-str-asposeslidesexportisaveoptions}
Sloučí více prezentací PowerPoint ve stejném formátu do jediného souboru prezentace.

```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| input_file_names | **List[str]** | Pole názvů vstupních souborů prezentací. |
| output_file_name | **str** | Název výstupního souboru výsledné sloučené prezentace. |
| options | [`ISaveOptions`](/slides/python-net/cs/aspose.slides.export/isaveoptions) | Další možnosti, které určují, jak bude sloučená prezentace uložena. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, když jsou názvy vstupních souborů neplatné nebo se formáty neshodují. |

## process(input_file_names, output_stream, options) {#liststr-iorawiobase-asposeslidesexportisaveoptions}
Sloučí více prezentací PowerPoint ve stejném formátu do jediného souboru prezentace.

```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| input_file_names | **List[str]** | Pole názvů vstupních souborů prezentací. |
| output_stream | **io.RawIOBase** | Výstupní proud. |
| options | [`ISaveOptions`](/slides/python-net/cs/aspose.slides.export/isaveoptions) | Další možnosti, které určují, jak bude sloučená prezentace uložena. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, když jsou názvy vstupních souborů neplatné nebo se formáty neshodují. |

### Viz také
* třída [`ISaveOptions`](/slides/python-net/cs/aspose.slides.export/isaveoptions)
* třída [`Merger`](/slides/python-net/cs/aspose.slides.lowcode/merger)
* modul [`aspose.slides.lowcode`](/slides/python-net/cs/aspose.slides.lowcode)
* knihovna [`Aspose.Slides`](/slides/python-net)