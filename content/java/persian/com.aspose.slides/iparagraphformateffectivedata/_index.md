---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides برای Java مرجع API
description: شیء غیرقابل تغییر که ویژگی‌های قالب‌بندی مؤثر پاراگراف را شامل می‌شود.
type: docs
url: /fa/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

شیء غیرقابل تغییر که ویژگی‌های قالب‌بندی مؤثر پاراگراف را شامل می‌شود.

--------------------

این اینترفیس همراه با اینترفیس [IParagraphFormat](../../com.aspose.slides/iparagraphformat) برای بازگرداندن مقادیر قالب‌بندی مؤثر با اعمال ارث‌بری استفاده می‌شود.
## متدها

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


Returns a bullet format of a paragraph. فقط خواندنی [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**باز می‌گرداند:**  
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```


Returns a depth of a paragraph. فقط خواندنی short.

**باز می‌گرداند:**  
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Returns the text alignment in a paragraph. فقط خواندنی [TextAlignment](../../com.aspose.slides/textalignment).

**باز می‌گرداند:**  
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```


Returns the amount of space between base lines in a paragraph. فقط خواندنی float.

**باز می‌گرداند:**  
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```


Returns the amount of space before the first line in a paragraph. فقط خواندنی float.

**باز می‌گرداند:**  
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```


Returns the amount of space after the last line in a paragraph. فقط خواندنی float.

**باز می‌گرداند:**  
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```


Determines whether the East Asian line break is used in a paragraph. فقط خواندنی boolean.

**باز می‌گرداند:**  
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```


Determines whether the Right to Left writing is used in a paragraph. فقط خواندنی boolean.

**باز می‌گرداند:**  
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```


Determines whether the Latin line break is used in a paragraph. فقط خواندنی boolean.

**باز می‌گرداند:**  
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```


Determines whether the hanging punctuation is used in a paragraph. فقط خواندنی boolean.

**باز می‌گرداند:**  
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```


Returns the left margin in a paragraph. فقط خواندنی float.

**باز می‌گرداند:**  
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```


Returns the right margin in a paragraph. فقط خواندنی float.

**باز می‌گرداند:**  
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```


Returns paragraph First Line Indent/Hanging Indent. Hanging Indent can be defined with negative values. فقط خواندنی float.

**باز می‌گرداند:**  
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```


Returns default tabulation size. فقط خواندنی float.

**باز می‌گرداند:**  
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```


Returns tabulations of a paragraph. فقط خواندنی ITabEffectiveData[].

**باز می‌گرداند:**  
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```


Returns a font alignment in a paragraph. فقط خواندنی [FontAlignment](../../com.aspose.slides/fontalignment).

**باز می‌گرداند:**  
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```


Returns default portion format of a paragraph. فقط خواندنی [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**باز می‌گرداند:**  
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)