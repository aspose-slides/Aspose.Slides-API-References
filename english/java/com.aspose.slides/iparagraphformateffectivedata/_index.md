---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective paragraph formatting properties.
type: docs
weight: 958
url: /java/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

Immutable object which contains effective paragraph formatting properties.

--------------------

This interface is used together with the [IParagraphFormat](../../com.aspose.slides/iparagraphformat) interface to return effective formatting values with inheritance applied.
## Methods

| Method | Description |
| --- | --- |
| [getBullet()](#getBullet--) | Returns a bullet format of a paragraph. |
| [getDepth()](#getDepth--) | Returns a depth of a paragraph. |
| [getAlignment()](#getAlignment--) | Returns the text alignment in a paragraph. |
| [getSpaceWithin()](#getSpaceWithin--) | Returns the amount of space between base lines in a paragraph. |
| [getSpaceBefore()](#getSpaceBefore--) | Returns the amount of space before the first line in a paragraph. |
| [getSpaceAfter()](#getSpaceAfter--) | Returns the amount of space after the last line in a paragraph. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Determines whether the East Asian line break is used in a paragraph. |
| [getRightToLeft()](#getRightToLeft--) | Determines whether the Right to Left writing is used in a paragraph. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Determines whether the Latin line break is used in a paragraph. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Determines whether the hanging punctuation is used in a paragraph. |
| [getMarginLeft()](#getMarginLeft--) | Returns the left margin in a paragraph. |
| [getMarginRight()](#getMarginRight--) | Returns the right margin in a paragraph. |
| [getIndent()](#getIndent--) | Returns paragraph First Line Indent/Hanging Indent. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Returns default tabulation size. |
| [getTabs()](#getTabs--) | Returns tabulations of a paragraph. |
| [getFontAlignment()](#getFontAlignment--) | Returns a font alignment in a paragraph. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Returns default portion format of a paragraph. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```


Returns a bullet format of a paragraph. Read-only [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**Returns:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```


Returns a depth of a paragraph. Read-only short.

**Returns:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Returns the text alignment in a paragraph. Read-only [TextAlignment](../../com.aspose.slides/textalignment).

**Returns:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```


Returns the amount of space between base lines in a paragraph. Read-only float.

**Returns:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```


Returns the amount of space before the first line in a paragraph. Read-only float.

**Returns:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```


Returns the amount of space after the last line in a paragraph. Read-only float.

**Returns:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```


Determines whether the East Asian line break is used in a paragraph. Read-only boolean.

**Returns:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```


Determines whether the Right to Left writing is used in a paragraph. Read-only boolean.

**Returns:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```


Determines whether the Latin line break is used in a paragraph. Read-only boolean.

**Returns:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```


Determines whether the hanging punctuation is used in a paragraph. Read-only boolean.

**Returns:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```


Returns the left margin in a paragraph. Read-only float.

**Returns:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```


Returns the right margin in a paragraph. Read-only float.

**Returns:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```


Returns paragraph First Line Indent/Hanging Indent. Hanging Indent can be defined with negative values. Read-only float.

**Returns:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```


Returns default tabulation size. Read-only float.

**Returns:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```


Returns tabulations of a paragraph. Read-only ITabEffectiveData[].

**Returns:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```


Returns a font alignment in a paragraph. Read-only [FontAlignment](../../com.aspose.slides/fontalignment).

**Returns:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```


Returns default portion format of a paragraph. Read-only [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**Returns:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)
