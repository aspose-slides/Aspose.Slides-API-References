---
title: process method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.lowcode/merger/process/
weight: 10
---
## process(input_file_names, output_file_name) {#liststr-str}
Slår samman flera PowerPoint-presentationer av samma format till en enda presentationsfil.

```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| input_file_names | **List[str]** | En array med filnamnen för inmatningspresentationerna. |
| output_file_name | **str]** | Utdatafilnamnet för den resulterande sammanfogade presentationsfilen. |

### Undantag

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas när inmatningsfilnamnen är ogiltiga eller formaten inte matchar. |

## process(input_file_names, output_stream) {#liststr-iorawiobase}
Slår samman flera PowerPoint-presentationer av samma format till en enda presentationsfil.

```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| input_file_names | **List[str]** | En array med filnamnen för inmatningspresentationerna. |
| output_stream | **io.RawIOBase** | Utdataströmmen. |

### Undantag

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas när inmatningsfilnamnen är ogiltiga eller formaten inte matchar. |

## process(input_file_names, output_file_name, options) {#liststr-str-asposeslidesexportisaveoptions}
Slår samman flera PowerPoint-presentationer av samma format till en enda presentationsfil.

```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| input_file_names | **List[str]** | En array med filnamnen för inmatningspresentationerna. |
| output_file_name | **str** | Utdatafilnamnet för den resulterande sammanfogade presentationsfilen. |
| options | [`ISaveOptions`](/slides/python-net/sv/aspose.slides.export/isaveoptions) | De extra alternativ som definierar hur den sammanslagna presentationen sparas. |

### Undantag

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas när inmatningsfilnamnen är ogiltiga eller formaten inte matchar. |

## process(input_file_names, output_stream, options) {#liststr-iorawiobase-asposeslidesexportisaveoptions}
Slår samman flera PowerPoint-presentationer av samma format till en enda presentationsfil.

```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| input_file_names | **List[str]** | En array med filnamnen för inmatningspresentationerna. |
| output_stream | **io.RawIOBase** | Utdataströmmen. |
| options | [`ISaveOptions`](/slides/python-net/sv/aspose.slides.export/isaveoptions) | De extra alternativ som definierar hur den sammanslagna presentationen sparas. |

### Undantag

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas när inmatningsfilnamnen är ogiltiga eller formaten inte matchar. |

### Se också
* klass [`ISaveOptions`](/slides/python-net/sv/aspose.slides.export/isaveoptions)
* klass [`Merger`](/slides/python-net/sv/aspose.slides.lowcode/merger)
* modul [`aspose.slides.lowcode`](/slides/python-net/sv/aspose.slides.lowcode)
* bibliotek [`Aspose.Slides`](/slides/python-net)