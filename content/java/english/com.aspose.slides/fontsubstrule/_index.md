---
title: FontSubstRule
second_title: Aspose.Slides for Java API Reference
description: Represents font subtituition information
type: docs
weight: 208
url: /com.aspose.slides/fontsubstrule/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

Represents font subtituition information
## Constructors

| Constructor | Description |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Creates new instance. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | Creates new instance. |
## Methods

| Method | Description |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Font to substitute. |
| [getDestFont()](#getDestFont--) | Font to use for substitution. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Rule to apply for substitution. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```


Creates new instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Source font. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Destination font. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```


Creates new instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Source font. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Destination font. |
| fontSubstRule | int | Font subst rule. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```


Font to substitute. Read-only [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```


Font to use for substitution. Read-only [IFontData](../../com.aspose.slides/ifontdata).

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```


Rule to apply for substitution. Read-only [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Returns:**
int
