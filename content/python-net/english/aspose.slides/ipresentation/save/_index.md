---
title: save method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ipresentation/save/
weight: 50
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



## save {#string-asposeslidesexportsaveformat}
Saves all slides of a presentation to a file with the specified format.


```python
def save(self, fname, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| fname | string | Path to the created file. |
| format | aspose.slides.export.SaveFormat | Format of the exported data. |



## save {#systemiostream-asposeslidesexportsaveformat}
Saves all slides of a presentation to a stream in the specified format.


```python
def save(self, stream, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | System.IO.Stream | Output stream. |
| format | aspose.slides.export.SaveFormat | Format of the exported data. |



## save {#string-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Saves all slides of a presentation to a file with the specified format and with additional options.


```python
def save(self, fname, format, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| fname | string | Path to the created file. |
| format | aspose.slides.export.SaveFormat | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/aspose.slides.export/isaveoptions) | Additional format options. |



## save {#systemiostream-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Saves all slides of a presentation to a stream in the specified format and with additional options.


```python
def save(self, stream, format, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | System.IO.Stream | Output stream. |
| format | aspose.slides.export.SaveFormat | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/aspose.slides.export/isaveoptions) | Additional format options. |

## Exceptions

| Exception | Description |
| :- | :- |
| .NET type System.NotSupportedException | If you try to save encrypted file in <br/>            none Office 2007-2010 format |



## save {#string-listint-asposeslidesexportsaveformat}
Saves specified slides of a presentation to a file with the specified format.


```python
def save(self, fname, slides, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| fname | string | Path to the created file. |
| slides | List[int] | Array with slide positions, starting from 1. |
| format | aspose.slides.export.SaveFormat | Format of the exported data. |

## Exceptions

| Exception | Description |
| :- | :- |
| .NET type System.ArgumentNullException | When stream or slides parameter is null. |
| .NET type System.ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| .NET type System.InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



## save {#systemiostream-listint-asposeslidesexportsaveformat}
Saves specified slides of a presentation to a stream in the specified format.


```python
def save(self, stream, slides, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | System.IO.Stream | Output stream. |
| slides | List[int] | Array with slide positions, starting from 1. |
| format | aspose.slides.export.SaveFormat | Format of the exported data. |

## Exceptions

| Exception | Description |
| :- | :- |
| .NET type System.ArgumentNullException | When stream or slides parameter is null. |
| .NET type System.ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| .NET type System.InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



## save {#string-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Saves specified slides of a presentation to a file with the specified format.


```python
def save(self, fname, slides, format, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| fname | string | Path to the created file. |
| slides | List[int] | Array with slide positions, starting from 1. |
| format | aspose.slides.export.SaveFormat | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/aspose.slides.export/isaveoptions) | Additional format options. |

## Exceptions

| Exception | Description |
| :- | :- |
| .NET type System.ArgumentNullException | When stream or slides parameter is null. |
| .NET type System.ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| .NET type System.InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



## save {#systemiostream-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
Saves specified slides of a presentation to a stream in the specified format.


```python
def save(self, stream, slides, format, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | System.IO.Stream | Output stream. |
| slides | List[int] | Array with slide positions, starting from 1. |
| format | aspose.slides.export.SaveFormat | Format of the exported data. |
| options | [`ISaveOptions`](/slides/python-net/aspose.slides.export/isaveoptions) | Additional format options. |

## Exceptions

| Exception | Description |
| :- | :- |
| .NET type System.ArgumentNullException | When stream or slides parameter is null. |
| .NET type System.ArgumentOutOfRangeException | When slides parameter contains wrong page numbers. |
| .NET type System.InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



