---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Android via Java API 参考
description: 不可变对象，包含有效的段落格式属性。
type: docs
url: /zh/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

不可变对象，包含有效的段落格式属性。

--------------------

此接口与 [IParagraphFormat](../../com.aspose.slides/iparagraphformat) 接口一起使用，以返回已应用继承的有效格式化值。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBullet()](#getBullet--) | 返回段落的项目符号格式。 |
| [getDepth()](#getDepth--) | 返回段落的深度。 |
| [getAlignment()](#getAlignment--) | 返回段落的文本对齐方式。 |
| [getSpaceWithin()](#getSpaceWithin--) | 返回段落基线之间的间距。 |
| [getSpaceBefore()](#getSpaceBefore--) | 返回段落第一行之前的间距。 |
| [getSpaceAfter()](#getSpaceAfter--) | 返回段落最后一行之后的间距。 |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | 确定段落是否使用东亚换行。 |
| [getRightToLeft()](#getRightToLeft--) | 确定段落是否使用从右到左书写。 |
| [getLatinLineBreak()](#getLatinLineBreak--) | 确定段落是否使用拉丁换行。 |
| [getHangingPunctuation()](#getHangingPunctuation--) | 确定段落是否使用悬挂标点。 |
| [getMarginLeft()](#getMarginLeft--) | 返回段落的左侧边距。 |
| [getMarginRight()](#getMarginRight--) | 返回段落的右侧边距。 |
| [getIndent()](#getIndent--) | 返回段落的首行缩进/悬挂缩进。 |
| [getDefaultTabSize()](#getDefaultTabSize--) | 返回默认制表符大小。 |
| [getTabs()](#getTabs--) | 返回段落的制表符。 |
| [getFontAlignment()](#getFontAlignment--) | 返回段落的字体对齐方式。 |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | 返回段落的默认部分格式。 |

### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```

返回段落的项目符号格式。只读 [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)。

**返回：**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

返回段落的深度。只读 short。

**返回：**
short

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

返回段落的文本对齐方式。只读 [TextAlignment](../../com.aspose.slides/textalignment)。

**返回：**
int

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

返回段落基线之间的间距。只读 float。

**返回：**
float

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

返回段落第一行之前的间距。只读 float。

**返回：**
float

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

返回段落最后一行之后的间距。只读 float。

**返回：**
float

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```

确定段落是否使用东亚换行。只读 boolean。

**返回：**
boolean

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

确定段落是否使用从右到左书写。只读 boolean。

**返回：**
boolean

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```

确定段落是否使用拉丁换行。只读 boolean。

**返回：**
boolean

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```

确定段落是否使用悬挂标点。只读 boolean。

**返回：**
boolean

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

返回段落的左侧边距。只读 float。

**返回：**
float

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

返回段落的右侧边距。只读 float。

**返回：**
float

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

返回段落的首行缩进/悬挂缩进。悬挂缩进可以使用负值定义。只读 float。

**返回：**
float

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

返回默认制表符大小。只读 float。

**返回：**
float

### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```

返回段落的制表符。只读 ITabEffectiveData[]。

**返回：**
com.aspose.slides.ITabEffectiveData[]

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

返回段落的字体对齐方式。只读 [FontAlignment](../../com.aspose.slides/fontalignment)。

**返回：**
int

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```

返回段落的默认部分格式。只读 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)。

**返回：**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)