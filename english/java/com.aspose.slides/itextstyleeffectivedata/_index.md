---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Java API Reference
description:  Immutable object which contains effective text style properties.
type: docs
weight: 1069
url: /java/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Immutable object which contains effective text style properties.

--------------------

This interface is used together with the [ITextStyle](../../com.aspose.slides/itextstyle) interface to return effective formatting values with inheritance applied.
## Methods

| Method | Description |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Returns level of effective style. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Returns effective default paragraph properties. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```


Returns level of effective style.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Zero-based index of level. Must lay in 0..8 interval. |

**Returns:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Effective formatting of level [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```


Returns effective default paragraph properties. Read-only [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Returns:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)
