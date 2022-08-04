---
title: CellInvalidFormulaException
second_title: Aspose.Sildes for Java API Reference
description: p
 The exception that is thrown when a calculated formula is not correct or was not parsed.
type: docs
weight: 74
url: /java/com.aspose.slides/cellinvalidformulaexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

The exception that is thrown when a calculated formula is not correct or was not parsed.
## Constructors

| Constructor | Description |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | Initializes a new instance of the [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) class. |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | Initializes a new instance of the [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) class with a specified error message. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | Initializes a new instance of the [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) class with a specified error message and a reference to the inner exception that is the cause of this exception. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | Initializes a new instance of the [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) class with a specified error message and a cell reference that contains the invalid formula. |
## Methods

| Method | Description |
| --- | --- |
| [getReference()](#getReference--) | Gets a cell reference that contains the invalid formula. |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```


Initializes a new instance of the [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) class.

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```


Initializes a new instance of the [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) class with a specified error message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | A string that describes the error. |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```


Initializes a new instance of the [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) class with a specified error message and a reference to the inner exception that is the cause of this exception.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | A string that describes the error. |
| innerException | java.lang.RuntimeException | The exception that is the cause of the current exception. |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```


Initializes a new instance of the [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) class with a specified error message and a cell reference that contains the invalid formula.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | A string that describes the error. |
| reference | java.lang.String | A string that describes a reference to the inner exception |

### getReference() {#getReference--}
```
public final String getReference()
```


Gets a cell reference that contains the invalid formula.

**Returns:**
java.lang.String
