---
title: CellInvalidReferenceException
second_title: Aspose.Slides for Java API Reference
description:  The exception that is thrown when an invalid cell reference is encountered.
type: docs
weight: 75
url: /java/com.aspose.slides/cellinvalidreferenceexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

The exception that is thrown when an invalid cell reference is encountered.
## Constructors

| Constructor | Description |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | Initializes a new instance of the [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) class. |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | Initializes a new instance of the [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) class with a specified error message. |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | Initializes a new instance of the [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) class with a specified error message and a reference to the inner exception that is the cause of this exception. |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | Initializes a new instance of the [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) class with a specified error message and an invalid cell reference. |
## Methods

| Method | Description |
| --- | --- |
| [getReference()](#getReference--) | Gets an invalid cell reference. |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```


Initializes a new instance of the [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) class.

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```


Initializes a new instance of the [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) class with a specified error message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | A string that describes the error. |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```


Initializes a new instance of the [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) class with a specified error message and a reference to the inner exception that is the cause of this exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | A string that describes the error. |
| innerException | java.lang.RuntimeException | The exception that is the cause of the current exception. |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```


Initializes a new instance of the [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) class with a specified error message and an invalid cell reference.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | A string that describes the error. |
| reference | java.lang.String | An invalid cell reference. |

### getReference() {#getReference--}
```
public final String getReference()
```


Gets an invalid cell reference.

**Returns:**
java.lang.String
