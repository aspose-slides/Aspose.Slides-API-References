---
title: ColorOperation
second_title: Aspose.Slides for Java API Reference
description: Represents different color operations used for color transformations.
type: docs
url: /com.aspose.slides/coloroperation/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

Represents different color operations used for color transformations. Immutable object.
## Constructors

| Constructor | Description |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Creates new color transform operation. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Creates new color transform operation. |
## Methods

| Method | Description |
| --- | --- |
| [getOperationType()](#getOperationType--) | Returns or sets the type of an operation. |
| [getParameter()](#getParameter--) | Returns a parameter of an operation. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the two ColorOperation instances are equal. |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```


Creates new color transform operation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | int | Operation type. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```


Creates new color transform operation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | int | Operation type. |
| parameter | float | Operation parameter. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```


Returns or sets the type of an operation. Read-only [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**Returns:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```


Returns a parameter of an operation. Read-only float.

**Returns:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the two ColorOperation instances are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The ColorOperation to compare with the current ColorOperation. |

**Returns:**
boolean - **true** if the specified ColorOperation is equal to the current ColorOperation; otherwise, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table.

**Returns:**
int
