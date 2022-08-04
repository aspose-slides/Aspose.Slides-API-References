---
title: Field
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents a field.
type: docs
weight: 187
url: /java/com.aspose.slides/field/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IField](../../com.aspose.slides/ifield)
```
public final class Field extends DomObject<Portion> implements IField
```

Represents a field.
## Constructors

| Constructor | Description |
| --- | --- |
| [Field(Portion parentImmediate, Field field)](#Field-com.aspose.slides.Portion-com.aspose.slides.Field-) |  |
| [Field(Portion parentImmediate, FieldType fieldType)](#Field-com.aspose.slides.Portion-com.aspose.slides.FieldType-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Returns or sets field's type. |
| [setType(IFieldType value)](#setType-com.aspose.slides.IFieldType-) | Returns or sets field's type. |
| [getSlide()](#getSlide--) | Returns the parent slide of a paragraph. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a paragraph. |
### Field(Portion parentImmediate, Field field) {#Field-com.aspose.slides.Portion-com.aspose.slides.Field-}
```
 Field(Portion parentImmediate, Field field)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | [Portion](../../com.aspose.slides/portion) |  |
| field | [Field](../../com.aspose.slides/field) |  |

### Field(Portion parentImmediate, FieldType fieldType) {#Field-com.aspose.slides.Portion-com.aspose.slides.FieldType-}
```
 Field(Portion parentImmediate, FieldType fieldType)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | [Portion](../../com.aspose.slides/portion) |  |
| fieldType | [FieldType](../../com.aspose.slides/fieldtype) |  |

### getType() {#getType--}
```
public final IFieldType getType()
```


Returns or sets field's type. Read/write [IFieldType](../../com.aspose.slides/ifieldtype).

**Returns:**
[IFieldType](../../com.aspose.slides/ifieldtype)
### setType(IFieldType value) {#setType-com.aspose.slides.IFieldType-}
```
public final void setType(IFieldType value)
```


Returns or sets field's type. Read/write [IFieldType](../../com.aspose.slides/ifieldtype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFieldType](../../com.aspose.slides/ifieldtype) |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Returns the parent slide of a paragraph. Read-only [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returns the parent presentation of a paragraph. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)
