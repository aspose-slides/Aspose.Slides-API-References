---
title: CellCircularReferenceException
second_title: Aspose.Slides for Java API Reference
description: The exception that is thrown when one or more circular references are detected where a formula refers to its own cell either directly or indirectly.
type: docs
weight: 72
url: /java/com.aspose.slides/cellcircularreferenceexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

The exception that is thrown when one or more circular references are detected where a formula refers to its own cell either directly or indirectly.
## Constructors

| Constructor | Description |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | Initializes a new instance of the [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) class. |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | Initializes a new instance of the [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) class with a specified error message. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | Initializes a new instance of the [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) class with a specified error message and a reference to the inner exception that is the cause of this exception. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | Initializes a new instance of the [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) class with a specified error message and circular cell reference. |
## Methods

| Method | Description |
| --- | --- |
| [getReference()](#getReference--) | Gets a circular cell reference. |
### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```


Initializes a new instance of the [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) class.

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```


Initializes a new instance of the [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) class with a specified error message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | A string that describes the error. |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```


Initializes a new instance of the [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) class with a specified error message and a reference to the inner exception that is the cause of this exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | A string that describes the error. |
| innerException | java.lang.RuntimeException | The exception that is the cause of the current exception. |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```


Initializes a new instance of the [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) class with a specified error message and circular cell reference.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | A string that describes the error. |
| reference | java.lang.String | A circular cell reference. |

### getReference() {#getReference--}
```
public final String getReference()
```


Gets a circular cell reference.

**Returns:**
java.lang.String
