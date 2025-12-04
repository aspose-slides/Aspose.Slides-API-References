---
title: process method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.lowcode/merger/process/
weight: 10
---


## process {#liststr-str}
Merges multiple PowerPoint presentations of the same format into a single presentation file.


```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| input_file_names | **List[str]** | An array of the input presentation file names. |
| output_file_name | **str** | The output file name of the resulting merged presentation file. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown when input file names are invalid or formats do not match. |


## process {#liststr-iorawiobase}
Merges multiple PowerPoint presentations of the same format into a single presentation file.


```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| input_file_names | **List[str]** | An array of the input presentation file names. |
| output_stream | **io.RawIOBase** | The output stream. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown when input file names are invalid or formats do not match. |


## process {#liststr-str-asposeslidesexportisaveoptions}
Merges multiple PowerPoint presentations of the same format into a single presentation file.


```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| input_file_names | **List[str]** | An array of the input presentation file names. |
| output_file_name | **str** | The output file name of the resulting merged presentation file. |
| options | [`ISaveOptions`](/slides/python-net/aspose.slides.export/isaveoptions) | The additional options that define how the merged presentation is saved. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown when input file names are invalid or formats do not match. |


## process {#liststr-iorawiobase-asposeslidesexportisaveoptions}
Merges multiple PowerPoint presentations of the same format into a single presentation file.


```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| input_file_names | **List[str]** | An array of the input presentation file names. |
| output_stream | **io.RawIOBase** | The output stream. |
| options | [`ISaveOptions`](/slides/python-net/aspose.slides.export/isaveoptions) | The additional options that define how the merged presentation is saved. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown when input file names are invalid or formats do not match. |



### See Also
* class [`ISaveOptions`](/slides/python-net/aspose.slides.export/isaveoptions)
* class [`Merger`](/slides/python-net/aspose.slides.lowcode/merger)
* module [`aspose.slides.lowcode`](/slides/python-net/aspose.slides.lowcode)
* library [`Aspose.Slides`](/slides/python-net)

