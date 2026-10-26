---
title: process method
second_title: Aspose.Slides dla Pythona poprzez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.lowcode/merger/process/
weight: 10
---
## process(input_file_names, output_file_name) {#liststr-str}
Łączy wiele prezentacji PowerPoint o tym samym formacie w jeden plik prezentacji.

```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| input_file_names | **List[str]** | Tablica nazw plików wejściowych prezentacji. |
| output_file_name | **str** | Nazwa pliku wyjściowego wynikowej połączonej prezentacji. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, gdy nazwy plików wejściowych są nieprawidłowe lub formaty nie pasują. |

## process(input_file_names, output_stream) {#liststr-iorawiobase}
Łączy wiele prezentacji PowerPoint o tym samym formacie w jeden plik prezentacji.

```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| input_file_names | **List[str]** | Tablica nazw plików wejściowych prezentacji. |
| output_stream | **io.RawIOBase** | Strumień wyjściowy. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, gdy nazwy plików wejściowych są nieprawidłowe lub formaty nie pasują. |

## process(input_file_names, output_file_name, options) {#liststr-str-asposeslidesexportisaveoptions}
Łączy wiele prezentacji PowerPoint o tym samym formacie w jeden plik prezentacji.

```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| input_file_names | **List[str]** | Tablica nazw plików wejściowych prezentacji. |
| output_file_name | **str** | Nazwa pliku wyjściowego wynikowej połączonej prezentacji. |
| options | [`ISaveOptions`](/slides/python-net/pl/aspose.slides.export/isaveoptions) | Dodatkowe opcje określające sposób zapisu połączonej prezentacji. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, gdy nazwy plików wejściowych są nieprawidłowe lub formaty nie pasują. |

## process(input_file_names, output_stream, options) {#liststr-iorawiobase-asposeslidesexportisaveoptions}
Łączy wiele prezentacji PowerPoint o tym samym formacie w jeden plik prezentacji.

```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| input_file_names | **List[str]** | Tablica nazw plików wejściowych prezentacji. |
| output_stream | **io.RawIOBase** | Strumień wyjściowy. |
| options | [`ISaveOptions`](/slides/python-net/pl/aspose.slides.export/isaveoptions) | Dodatkowe opcje określające sposób zapisu połączonej prezentacji. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, gdy nazwy plików wejściowych są nieprawidłowe lub formaty nie pasują. |

### Zobacz także
* klasa [`ISaveOptions`](/slides/python-net/pl/aspose.slides.export/isaveoptions)
* klasa [`Merger`](/slides/python-net/pl/aspose.slides.lowcode/merger)
* moduł [`aspose.slides.lowcode`](/slides/python-net/pl/aspose.slides.lowcode)
* biblioteka [`Aspose.Slides`](/slides/python-net)