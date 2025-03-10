---
title: add method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/captionscollection/add/
weight: 10
---


## add {#str-str}
Adds WebVTT closed captions to the end of the collection.

### Returns

The added [`ICaptions`](/slides/python-net/aspose.slides/icaptions) instance.



```python
def add(self, label, file_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| label | **str** | The label of the closed captions. |
| file_path | **str** | The path to the WebVTT file. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Thrown if `file_path` is `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown if `file_path` is empty. |


## add {#str-iorawiobase}
Adds WebVTT closed captions to the end of the collection from a stream.

### Returns

The added [`ICaptions`](/slides/python-net/aspose.slides/icaptions) instance.



```python
def add(self, label, stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| label | **str** | The label of the closed captions. |
| stream | **io.RawIOBase** | The input stream containing data in WebVTT format. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Thrown if `stream` is `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown if the input data is not in WebVTT format. |



### See Also
* class [`CaptionsCollection`](/slides/python-net/aspose.slides/captionscollection)
* class [`ICaptions`](/slides/python-net/aspose.slides/icaptions)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

