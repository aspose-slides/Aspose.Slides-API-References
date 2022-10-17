---
title: ITextStyle
second_title: Aspose.Slides for Android via Java API Reference
description:  Text style formatting properties.
type: docs
weight: 1068
url: /androidjava/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Text style formatting properties.
## Methods

| Method | Description |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | If level of style exist returns it, otherwise returns null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Default paragraph propertiies. |
| [getEffective()](#getEffective--) | Gets effective text style formatting data with the inheritance applied. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```


If level of style exist returns it, otherwise returns null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Zero-based index of level. Must lay in 0..8 interval. |

**Returns:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Formatting of level [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```


Default paragraph propertiies. Read-only [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Returns:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```


Gets effective text style formatting data with the inheritance applied.

**Returns:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - A [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).
