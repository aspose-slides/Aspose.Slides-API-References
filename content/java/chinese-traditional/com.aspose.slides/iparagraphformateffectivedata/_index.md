---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective paragraph formatting properties.
type: docs
url: /zh-hant/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

不可變的物件，包含有效的段落格式屬性。

--------------------

此介面與 [IParagraphFormat](../../com.aspose.slides/iparagraphformat) 介面結合使用，以在套用繼承後回傳有效的格式值。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getBullet()](#getBullet--) | 回傳段落的項目符號格式。 |
| [getDepth()](#getDepth--) | 回傳段落的深度。 |
| [getAlignment()](#getAlignment--) | 回傳段落中的文字對齊方式。 |
| [getSpaceWithin()](#getSpaceWithin--) | 回傳段落中基線之間的間距。 |
| [getSpaceBefore()](#getSpaceBefore--) | 回傳段落第一行之前的間距。 |
| [getSpaceAfter()](#getSpaceAfter--) | 回傳段落最後一行之後的間距。 |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | 判斷段落是否使用東亞換行。 |
| [getRightToLeft()](#getRightToLeft--) | 判斷段落是否使用從右至左書寫。 |
| [getLatinLineBreak()](#getLatinLineBreak--) | 判斷段落是否使用拉丁換行。 |
| [getHangingPunctuation()](#getHangingPunctuation--) | 判斷段落是否使用懸掛標點。 |
| [getMarginLeft()](#getMarginLeft--) | 回傳段落的左邊界。 |
| [getMarginRight()](#getMarginRight--) | 回傳段落的右邊界。 |
| [getIndent()](#getIndent--) | 回傳段落的首行縮排/懸掛縮排。 |
| [getDefaultTabSize()](#getDefaultTabSize--) | 回傳預設的定位點大小。 |
| [getTabs()](#getTabs--) | 回傳段落的定位點。 |
| [getFontAlignment()](#getFontAlignment--) | 回傳段落的字型對齊方式。 |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | 回傳段落的預設部份格式。 |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```

回傳段落的項目符號格式。唯讀 [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)。

**Returns:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

回傳段落的深度。唯讀 short。

**Returns:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

回傳段落中的文字對齊方式。唯讀 [TextAlignment](../../com.aspose.slides/textalignment)。

**Returns:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

回傳段落中基線之間的間距。唯讀 float。

**Returns:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

回傳段落第一行之前的間距。唯讀 float。

**Returns:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

回傳段落最後一行之後的間距。唯讀 float。

**Returns:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```

判斷段落是否使用東亞換行。唯讀 boolean。

**Returns:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

判斷段落是否使用從右至左書寫。唯讀 boolean。

**Returns:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```

判斷段落是否使用拉丁換行。唯讀 boolean。

**Returns:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```

判斷段落是否使用懸掛標點。唯讀 boolean。

**Returns:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

回傳段落的左邊界。唯讀 float。

**Returns:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

回傳段落的右邊界。唯讀 float。

**Returns:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

回傳段落的首行縮排/懸掛縮排。懸掛縮排可使用負值定義。唯讀 float。

**Returns:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

回傳預設的定位點大小。唯讀 float。

**Returns:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```

回傳段落的定位點。唯讀 ITabEffectiveData[]。

**Returns:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

回傳段落的字型對齊方式。唯讀 [FontAlignment](../../com.aspose.slides/fontalignment)。

**Returns:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```

回傳段落的預設部份格式。唯讀 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)。

**Returns:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)