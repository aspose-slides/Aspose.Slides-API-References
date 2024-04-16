---
title: Presentation constructor
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/presentation/__init__/
weight: 10
---


## __init__ {#}
This constructor creates new presentation from scratch.
            Created presentation has one empty slide.


```python
def __init__(self):
    ...
```



## __init__ {#loadoptions}
This constructor creates new presentation from scratch.
            Created presentation has one empty slide.


```python
def __init__(self, load_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| load_options | [`LoadOptions`](/slides/python-net/aspose.slides/loadoptions) | Additional load options. |


## __init__ {#iorawiobase}
This constructor is the primary mechanism for reading an existing Presentation.


```python
def __init__(self, stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Input stream. |


## __init__ {#str}
This constructor gets a source file path from which
             the contents of the Presentation are read.


```python
def __init__(self, file):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file | **str** | Input file. |

## Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown when input file has zero length |


## __init__ {#iorawiobase-loadoptions}
This constructor is the primary mechanism for reading an existing Presentation.


```python
def __init__(self, stream, load_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Input stream. |
| load_options | [`LoadOptions`](/slides/python-net/aspose.slides/loadoptions) | Additional load options. |


## __init__ {#str-loadoptions}
This constructor gets a source file path from which
            the contents of the Presentation are read.


```python
def __init__(self, file, load_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file | **str** | Input file. |
| load_options | [`LoadOptions`](/slides/python-net/aspose.slides/loadoptions) | Additional load options. |

## Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown when input file has zero length |



### See Also
* class [`LoadOptions`](/slides/python-net/aspose.slides/loadoptions)
* class [`Presentation`](/slides/python-net/aspose.slides/presentation)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

