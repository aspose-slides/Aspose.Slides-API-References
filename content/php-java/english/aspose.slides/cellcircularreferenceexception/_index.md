---
title: CellCircularReferenceException
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/cellcircularreferenceexception/
---

## CellCircularReferenceException class

 The exception that is thrown when one or more circular references are detected where a formula refers to its
 own cell either directly or indirectly.
 
### CellCircularReferenceException {#CellCircularReferenceException}

| Name | Description |
| --- | --- |
| CellCircularReferenceException() | Initializes a new instance of the CellCircularReferenceException class. |

 **Result:**
CellCircularReferenceException


---


### CellCircularReferenceException {#CellCircularReferenceException}

| Name | Description |
| --- | --- |
| CellCircularReferenceException(String) | Initializes a new instance of the CellCircularReferenceException class with a specified error message. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| message | String | A string that describes the error. |

 **Result:**
CellCircularReferenceException


---


### CellCircularReferenceException {#CellCircularReferenceException}

| Name | Description |
| --- | --- |
| CellCircularReferenceException(String, RuntimeException) | Initializes a new instance of the CellCircularReferenceException class with a specified error message and a reference to the inner exception that is the cause of this exception. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| message | String | A string that describes the error. |
| innerException | RuntimeException | The exception that is the cause of the current exception. |

 **Result:**
CellCircularReferenceException


---


### CellCircularReferenceException {#CellCircularReferenceException}

| Name | Description |
| --- | --- |
| CellCircularReferenceException(String, String) | Initializes a new instance of the CellCircularReferenceException class with a specified error message and circular cell reference. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| message | String | A string that describes the error. |
| reference | String | A circular cell reference. |

 **Result:**
CellCircularReferenceException


---


### getReference {#getReference}

| Name | Description |
| --- | --- |
| getReference () | Gets a circular cell reference. |

 **Returns:**
String


---


