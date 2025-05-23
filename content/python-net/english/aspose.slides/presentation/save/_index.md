﻿---
title: save method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/presentation/save/
weight: 110
---


## save {#asposeslidesexportxamlixamloptions}
Saves all slides of a presentation to a set of files representing XAML markup.


```python
def save(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/aspose.slides.export.xaml/ixamloptions) | The XAML format options. |


## save {#str-asposeslidesexportsaveformat}
Saves all slides of a presentation to a file with the specified format.


```python
def save(self, fname, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| fname | **str** | Path to the created file. |
| format | [`SaveFormat`](/slides/python-net/aspose.slides.export/saveformat) | Format of the exported data. |


## save {#iorawiobase-asposeslidesexportsaveformat}
Saves all slides of a presentation to a stream in the specified format.


```python
def save(self, stream, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| format | [`SaveFormat`](/slides/python-net/aspose.slides.export/saveformat) | Format of the exported data. |


## save {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}



```python
def save(self, fname, format, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| fname | **str** |  |
| format | [`SaveFormat`](/slides/python-net/aspose.slides.export/saveformat) |  |
| options | [`ISaveOptions`](/slides/python-net/aspose.slides.export/isaveoptions) |  |


## save {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Saves all slides of a presentation to a stream in the specified format and with additional options.


```python
def save(self, stream, format, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| format | [`SaveFormat`](/slides/python-net/aspose.slides.export/saveformat) | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/aspose.slides.export/isaveoptions) | Additional format options. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | If you try to save encrypted file in <br/>            none Office 2007-2010 format |


## save {#str-listint-asposeslidesexportsaveformat}
Saves specified slides of a presentation to a file with the specified format with page number keeping.


```python
def save(self, fname, slides, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| fname | **str** | Path to the created file. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| format | [`SaveFormat`](/slides/python-net/aspose.slides.export/saveformat) | Format of the exported data. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | When stream or slides parameter is None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | When slides parameter contains wrong page numbers. |
| **RuntimeError(Proxy error(InvalidOperationException))** | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save {#iorawiobase-listint-asposeslidesexportsaveformat}
Saves specified slides of a presentation to a stream in the specified format with page number keeping.


```python
def save(self, stream, slides, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| format | [`SaveFormat`](/slides/python-net/aspose.slides.export/saveformat) | Format of the exported data. |


## save {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Saves specified slides of a presentation to a file with the specified format with page number keeping.


```python
def save(self, fname, slides, format, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| fname | **str** | Path to the created file. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| format | [`SaveFormat`](/slides/python-net/aspose.slides.export/saveformat) | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/aspose.slides.export/isaveoptions) | Additional format options. |


## save {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Saves specified slides of a presentation to a stream in the specified format with page number keeping.


```python
def save(self, stream, slides, format, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| format | [`SaveFormat`](/slides/python-net/aspose.slides.export/saveformat) | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/aspose.slides.export/isaveoptions) | Additional format options. |

### Examples

The following example shows how to convert PowerPoint to PNG.

            The following example shows how to convert PowerPoint to PNG with custom dimensions.

            The following example shows how to convert PowerPoint to PNG with custom size.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | When stream or slides parameter is None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | When slides parameter contains wrong page numbers. |
| **RuntimeError(Proxy error(InvalidOperationException))** | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### See Also
* class [`ISaveOptions`](/slides/python-net/aspose.slides.export/isaveoptions)
* class [`IXamlOptions`](/slides/python-net/aspose.slides.export.xaml/ixamloptions)
* class [`Presentation`](/slides/python-net/aspose.slides/presentation)
* enumeration [`SaveFormat`](/slides/python-net/aspose.slides.export/saveformat)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

