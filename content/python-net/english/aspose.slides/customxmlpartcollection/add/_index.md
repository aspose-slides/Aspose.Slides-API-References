---
title: add method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/customxmlpartcollection/add/
weight: 10
---


## add {#str}
Adds new custom xml part.

### Returns

Created custom xml part.



```python
def add(self, xml_string):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| xml_string | **str** | The xml string of new part to be added. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString is `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString is empty or xml-data is invalid. |


## add {#bytes}
Adds new custom xml part.

### Returns

Created custom xml part.



```python
def add(self, xml_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| xml_data | **bytes** | The xml data of new part to be added. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData is `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData is empty or invalid. |


## add {#iorawiobase}
Adds new custom xml part.

### Returns

Created custom xml part.



```python
def add(self, input_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | The inputStream with xml data of new part to be added. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream is `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Data in inputStream is empty or invalid. |



### See Also
* class [`CustomXmlPartCollection`](/slides/python-net/aspose.slides/customxmlpartcollection)
* class [`ICustomXmlPart`](/slides/python-net/aspose.slides/icustomxmlpart)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

