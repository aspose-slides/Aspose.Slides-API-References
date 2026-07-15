---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: 不可變物件，包含有效的段落格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

不可變物件，包含有效的段落格式屬性。

--------------------

此介面與 [IParagraphFormat](../../com.aspose.slides/iparagraphformat) 介面一起使用，以回傳套用繼承的有效格式值。

## 方法

| Method | Description |
| --- | --- |
| [getBullet()](#getBullet--) | 傳回段落的項目符號格式。 |
| [getDepth()](#getDepth--) | 傳回段落的深度。 |
| [getAlignment()](#getAlignment--) | 傳回段落中的文字對齊方式。 |
| [getSpaceWithin()](#getSpaceWithin--) | 傳回段落基線之間的間距。 |
| [getSpaceBefore()](#getSpaceBefore--) | 傳回段落第一行之前的間距。 |
| [getSpaceAfter()](#getSpaceAfter--) | 傳回段落最後一行之後的間距。 |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | 判斷段落是否使用東亞換行。 |
| [getRightToLeft()](#getRightToLeft--) | 判斷段落是否使用從右至左的書寫方式。 |
| [getLatinLineBreak()](#getLatinLineBreak--) | 判斷段落是否使用拉丁換行。 |
| [getHangingPunctuation()](#getHangingPunctuation--) | 判斷段落是否使用懸掛標點。 |
| [getMarginLeft()](#getMarginLeft--) | 傳回段落的左邊距。 |
| [getMarginRight()](#getMarginRight--) | 傳回段落的右邊距。 |
| [getIndent()](#getIndent--) | 傳回段落的首行縮排/懸掛縮排。 |
| [getDefaultTabSize()](#getDefaultTabSize--) | 傳回預設的定位寬度。 |
| [getTabs()](#getTabs--) | 傳回段落的定位設定。 |
| [getFontAlignment()](#getFontAlignment--) | 傳回段落中的字型對齊方式。 |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | 傳回段落的預設部分格式。 |

### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```

傳回段落的項目符號格式。唯讀 [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)。

**返回:**  
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

傳回段落的深度。唯讀 short。

**返回:**  
short

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

傳回段落中的文字對齊方式。唯讀 [TextAlignment](../../com.aspose.slides/textalignment)。

**返回:**  
int

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

傳回段落基線之間的間距。唯讀 float。

**返回:**  
float

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

傳回段落第一行之前的間距。唯讀 float。

**返回:**  
float

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

傳回段落最後一行之後的間距。唯讀 float。

**返回:**  
float

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```

判斷段落是否使用東亞換行。唯讀 boolean。

**返回:**  
boolean

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

判斷段落是否使用從右至左的書寫方式。唯讀 boolean。

**返回:**  
boolean

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```

判斷段落是否使用拉丁換行。唯讀 boolean。

**返回:**  
boolean

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```

判斷段落是否使用懸掛標點。唯讀 boolean。

**返回:**  
boolean

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

傳回段落的左邊距。唯讀 float。

**返回:**  
float

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

傳回段落的右邊距。唯讀 float。

**返回:**  
float

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

傳回段落的首行縮排/懸掛縮排。懸掛縮排可使用負值定義。唯讀 float。

**返回:**  
float

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

傳回預設的定位寬度。唯讀 float。

**返回:**  
float

### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```

傳回段落的定位設定。唯讀 ITabEffectiveData[]。

**返回:**  
com.aspose.slides.ITabEffectiveData[]

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

傳回段落中的字型對齊方式。唯讀 [FontAlignment](../../com.aspose.slides/fontalignment)。

**返回:**  
int

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```

傳回段落的預設部分格式。唯讀 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)。

**返回:**  
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)