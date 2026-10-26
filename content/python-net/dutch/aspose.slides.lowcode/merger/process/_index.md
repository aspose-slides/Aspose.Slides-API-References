---
title: process method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.lowcode/merger/process/
weight: 10
---
## process(input_file_names, output_file_name) {#liststr-str}
Voegt meerdere PowerPoint-presentaties van hetzelfde formaat samen tot één presentatiebestand.


```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| input_file_names | **List[str]** | Een array met de invoer-presentatie-bestandsnamen. |
| output_file_name | **str** | De bestandsnaam van het resulterende samengevoegde presentatiebestand. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid wanneer de invoerbestandsnamen ongeldig zijn of de formaten niet overeenkomen. |


## process(input_file_names, output_stream) {#liststr-iorawiobase}
Voegt meerdere PowerPoint-presentaties van hetzelfde formaat samen tot één presentatiebestand.


```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| input_file_names | **List[str]** | Een array met de invoer-presentatie-bestandsnamen. |
| output_stream | **io.RawIOBase** | De uitvoerstroom. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid wanneer de invoerbestandsnamen ongeldig zijn of de formaten niet overeenkomen. |


## process(input_file_names, output_file_name, options) {#liststr-str-asposeslidesexportisaveoptions}
Voegt meerdere PowerPoint-presentaties van hetzelfde formaat samen tot één presentatiebestand.


```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| input_file_names | **List[str]** | Een array met de invoer-presentatie-bestandsnamen. |
| output_file_name | **str** | De bestandsnaam van het resulterende samengevoegde presentatiebestand. |
| options | [`ISaveOptions`](/slides/python-net/nl/aspose.slides.export/isaveoptions) | De extra opties die bepalen hoe de samengevoegde presentatie wordt opgeslagen. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid wanneer de invoerbestandsnamen ongeldig zijn of de formaten niet overeenkomen. |


## process(input_file_names, output_stream, options) {#liststr-iorawiobase-asposeslidesexportisaveoptions}
Voegt meerdere PowerPoint-presentaties van hetzelfde formaat samen tot één presentatiebestand.


```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| input_file_names | **List[str]** | Een array met de invoer-presentatie-bestandsnamen. |
| output_stream | **io.RawIOBase** | De uitvoerstroom. |
| options | [`ISaveOptions`](/slides/python-net/nl/aspose.slides.export/isaveoptions) | De extra opties die bepalen hoe de samengevoegde presentatie wordt opgeslagen. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid wanneer de invoerbestandsnamen ongeldig zijn of de formaten niet overeenkomen. |



### Zie ook
* klasse [`ISaveOptions`](/slides/python-net/nl/aspose.slides.export/isaveoptions)
* klasse [`Merger`](/slides/python-net/nl/aspose.slides.lowcode/merger)
* module [`aspose.slides.lowcode`](/slides/python-net/nl/aspose.slides.lowcode)
* bibliotheek [`Aspose.Slides`](/slides/python-net)