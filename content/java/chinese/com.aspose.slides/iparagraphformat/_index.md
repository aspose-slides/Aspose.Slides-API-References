---
title: IParagraphFormat
second_title: Aspose.Slides for Java API Reference
description: 本类包含段落格式属性。
type: docs
url: /zh/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

此类包含段落格式属性。不同于 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)，此类的所有属性均可写。

--------------------

此类用于返回和操作为特定段落定义的段落格式属性。这意味着在获取值时不应用继承，因此在大多数情况下您将获得表示“未定义”的值。

为了获取包括继承在内的有效格式参数值，您需要使用 [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) 方法，该方法返回一个 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) 实例。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBullet()](#getBullet--) | 返回段落的项目符号格式。 |
| [getDepth()](#getDepth--) | 返回或设置段落的深度。 |
| [setDepth(short value)](#setDepth-short-) | 返回或设置段落的深度。 |
| [getAlignment()](#getAlignment--) | 返回或设置段落中的文本对齐方式（不继承）。 |
| [setAlignment(int value)](#setAlignment-int-) | 返回或设置段落中的文本对齐方式（不继承）。 |
| [getSpaceWithin()](#getSpaceWithin--) | 返回或设置段落基线之间的间距。 |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | 返回或设置段落基线之间的间距。 |
| [getSpaceBefore()](#getSpaceBefore--) | 返回或设置段落首行之前的空间（不继承）。 |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | 返回或设置段落首行之前的空间（不继承）。 |
| [getSpaceAfter()](#getSpaceAfter--) | 返回或设置段落最后一行之后的空间（不继承）。 |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | 返回或设置段落最后一行之后的空间（不继承）。 |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | 判断段落是否使用东亚换行。 |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | 判断段落是否使用东亚换行。 |
| [getRightToLeft()](#getRightToLeft--) | 判断段落是否使用从右到左书写。 |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | 判断段落是否使用从右到左书写。 |
| [getLatinLineBreak()](#getLatinLineBreak--) | 判断段落是否使用拉丁换行。 |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | 判断段落是否使用拉丁换行。 |
| [getHangingPunctuation()](#getHangingPunctuation--) | 判断段落是否使用悬挂标点。 |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | 判断段落是否使用悬挂标点。 |
| [getMarginLeft()](#getMarginLeft--) | 返回或设置段落左边距（不继承）。 |
| [setMarginLeft(float value)](#setMarginLeft-float-) | 返回或设置段落左边距（不继承）。 |
| [getMarginRight()](#getMarginRight--) | 返回或设置段落右边距（不继承）。 |
| [setMarginRight(float value)](#setMarginRight-float-) | 返回或设置段落右边距（不继承）。 |
| [getIndent()](#getIndent--) | 返回或设置段落首行缩进/悬挂缩进（不继承）。 |
| [setIndent(float value)](#setIndent-float-) | 返回或设置段落首行缩进/悬挂缩进（不继承）。 |
| [getDefaultTabSize()](#getDefaultTabSize--) | 返回或设置默认制表位大小（不继承）。 |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | 返回或设置默认制表位大小（不继承）。 |
| [getTabs()](#getTabs--) | 返回段落的制表位。 |
| [getFontAlignment()](#getFontAlignment--) | 返回或设置段落中的字体对齐方式（不继承）。 |
| [setFontAlignment(int value)](#setFontAlignment-int-) | 返回或设置段落中的字体对齐方式（不继承）。 |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | 返回段落的默认文本块格式。 |
| [getEffective()](#getEffective--) | 获取应用继承后的有效段落格式数据。 |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

返回段落的项目符号格式。只读 [IBulletFormat](../../com.aspose.slides/ibulletformat)。

**返回：**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

返回或设置段落的深度。值 0 表示未定义的值。读/写 short。

**返回：**
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

返回或设置段落的深度。值 0 表示未定义的值。读/写 short。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

返回或设置段落中的文本对齐方式（不继承）。读/写 [TextAlignment](../../com.aspose.slides/textalignment)。

**返回：**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

返回或设置段落中的文本对齐方式（不继承）。读/写 [TextAlignment](../../com.aspose.slides/textalignment)。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

返回或设置段落基线之间的间距。正值表示百分比，负值表示点数大小。不继承。读/写 float。

**返回：**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

返回或设置段落基线之间的间距。正值表示百分比，负值表示点数大小。不继承。读/写 float。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

返回或设置段落首行之前的空间（不继承）。正值指定应为字体大小的百分比，负值指定点数大小。读/写 float。

**返回：**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

返回或设置段落首行之前的空间（不继承）。正值指定应为字体大小的百分比，负值指定点数大小。读/写 float。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

返回或设置段落最后一行之后的空间（不继承）。正值指定应为字体大小的百分比，负值指定点数大小。读/写 float。

**返回：**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

返回或设置段落最后一行之后的空间（不继承）。正值指定应为字体大小的百分比，负值指定点数大小。读/写 float。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

判断段落是否使用东亚换行。不继承。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

判断段落是否使用东亚换行。不继承。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

判断段落是否使用从右到左书写。不继承。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

判断段落是否使用从右到左书写。不继承。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

判断段落是否使用拉丁换行。不继承。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

判断段落是否使用拉丁换行。不继承。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

判断段落是否使用悬挂标点。不继承。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

判断段落是否使用悬挂标点。不继承。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

返回或设置段落左边距（不继承）。读/写 float。

**返回：**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

返回或设置段落左边距（不继承）。读/写 float。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

返回或设置段落右边距（不继承）。读/写 float。

**返回：**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

返回或设置段落右边距（不继承）。读/写 float。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

返回或设置段落首行缩进/悬挂缩进（不继承）。悬挂缩进可使用负值。读/写 float。

**返回：**
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

返回或设置段落首行缩进/悬挂缩进（不继承）。悬挂缩进可使用负值。读/写 float。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

返回或设置默认制表位大小（不继承）。读/写 float。

**返回：**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

返回或设置默认制表位大小（不继承）。读/写 float。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

返回段落的制表位。不继承。只读 [ITabCollection](../../com.aspose.slides/itabcollection)。

**返回：**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

返回或设置段落中的字体对齐方式（不继承）。读/写 [FontAlignment](../../com.aspose.slides/fontalignment)。

**返回：**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

返回或设置段落中的字体对齐方式（不继承）。读/写 [FontAlignment](../../com.aspose.slides/fontalignment)。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

返回段落的默认文本块格式。不继承。只读 [IPortionFormat](../../com.aspose.slides/iportionformat)。

**返回：**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

获取应用继承后的有效段落格式数据。

**返回：**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).