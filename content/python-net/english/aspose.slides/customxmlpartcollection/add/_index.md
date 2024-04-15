---
title: add method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/customxmlpartcollection/add/
weight: 10
---


## add {#string}
Adds new custom xml part.

### Returns

Created custom xml part.



```python
def add(self, xml_string):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| xml_string | string | The xml string of new part to be added. |

## Exceptions

| Exception | Description |
| :- | :- |
| **System.ArgumentNullException** | xmlString is `null`. |
| **System.ArgumentException** | xmlString is empty or xml-data is invalid. |



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
| xml_data | bytes | The xml data of new part to be added. |

## Exceptions

| Exception | Description |
| :- | :- |
| **System.ArgumentNullException** | xmlData is `null`. |
| **System.ArgumentException** | xmlData is empty or invalid. |



## add {#systemiostream}
Adds new custom xml part.

### Returns

Created custom xml part.



```python
def add(self, input_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| input_stream | System.IO.Stream | The inputStream with xml data of new part to be added. |

## Exceptions

| Exception | Description |
| :- | :- |
| **System.ArgumentNullException** | inputStream is `null`. |
| **System.ArgumentException** | Data in inputStream is empty or invalid. |



### See Also
* class [`CustomXmlPartCollection`](/slides/python-net/aspose.slides/customxmlpartcollection)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
