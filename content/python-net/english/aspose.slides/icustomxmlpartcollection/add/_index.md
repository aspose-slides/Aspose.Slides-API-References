---
title: add method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/icustomxmlpartcollection/add/
weight: 10
---


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
| .NET type System.ArgumentNullException | xmlData is `null`. |
| .NET type System.ArgumentException | xmlData is empty or invalid. |



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
| .NET type System.ArgumentNullException | xmlString is `null`. |
| .NET type System.ArgumentException | xmlString is empty or xml-data is invalid. |



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
| .NET type System.ArgumentNullException | inputStream is `null`. |
| .NET type System.ArgumentException | Data in inputStream is empty or Sinvalid. |



