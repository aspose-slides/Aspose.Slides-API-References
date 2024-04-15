---
title: save method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/presentation/save/
weight: 60
---


## save {#asposeslidesexportxamlixamloptions}
Saves all slides of a presentation to a set of files representing XAML markup.


```python
def save(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | **aspose.slides.export.xaml.IXamlOptions** | The XAML format options. |



## save {#str-asposeslidesexportsaveformat}
Saves all slides of a presentation to a file with the specified format.


```python
def save(self, fname, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| fname | **str** | Path to the created file. |
| format | **aspose.slides.export.SaveFormat** | Format of the exported data. |



## save {#iorawiobase-asposeslidesexportsaveformat}
Saves all slides of a presentation to a stream in the specified format.


```python
def save(self, stream, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| format | **aspose.slides.export.SaveFormat** | Format of the exported data. |



## save {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}



```python
def save(self, fname, format, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| fname | **str** |  |
| format | **aspose.slides.export.SaveFormat** |  |
| options | **aspose.slides.export.ISaveOptions** |  |



## save {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Saves all slides of a presentation to a stream in the specified format and with additional options.


```python
def save(self, stream, format, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Output stream. |
| format | **aspose.slides.export.SaveFormat** | Format of the exported data. |
| options | **aspose.slides.export.ISaveOptions** | Additional format options. |

## Exceptions

| Exception | Description |
| :- | :- |
| **System.NotSupportedException** | If you try to save encrypted file in <br/>            none Office 2007-2010 format |



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
| format | **aspose.slides.export.SaveFormat** | Format of the exported data. |

## Exceptions

| Exception | Description |
| :- | :- |
| **System.ArgumentNullException** | When stream or slides parameter is null. |
| **System.ArgumentOutOfRangeException** | When slides parameter contains wrong page numbers. |
| **System.InvalidOperationException** | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



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
| format | **aspose.slides.export.SaveFormat** | Format of the exported data. |



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
| format | **aspose.slides.export.SaveFormat** | Format of the exported data. |
| options | **aspose.slides.export.ISaveOptions** | Additional format options. |



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
| format | **aspose.slides.export.SaveFormat** | Format of the exported data. |
| options | **aspose.slides.export.ISaveOptions** | Additional format options. |

## Exceptions

| Exception | Description |
| :- | :- |
| **System.ArgumentNullException** | When stream or slides parameter is null. |
| **System.ArgumentOutOfRangeException** | When slides parameter contains wrong page numbers. |
| **System.InvalidOperationException** | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### See Also
* class [`Presentation`](/slides/python-net/aspose.slides/presentation)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
