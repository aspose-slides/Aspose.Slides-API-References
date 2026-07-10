---
title: IParagraphFormat
second_title: Aspose.Slides for Android via Java API Reference
description: 此类包含段落格式属性。
type: docs
url: /zh/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

此类包含段落格式属性。不同于 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)，此类的所有属性都是可写的。

--------------------

此类用于返回和操作为特定段落定义的段落格式属性。这意味着在获取值时不会应用继承，因此在大多数情况下您将得到表示“未定义”的值。

为了获取包括继承在内的有效格式参数值，您需要使用 [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) 方法，该方法返回一个 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) 实例。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBullet()](#getBullet--) | 返回段落的项目符号格式。 |
| [getDepth()](#getDepth--) | 返回或设置段落的深度。 |
| [setDepth(short value)](#setDepth-short-) | 返回或设置段落的深度。 |
| [getAlignment()](#getAlignment--) | 返回或设置段落中不使用继承的文本对齐方式。 |
| [setAlignment(int value)](#setAlignment-int-) | 返回或设置段落中不使用继承的文本对齐方式。 |
| [getSpaceWithin()](#getSpaceWithin--) | 返回或设置段落中基线之间的空间量。 |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | 返回或设置段落中基线之间的空间量。 |
| [getSpaceBefore()](#getSpaceBefore--) | 返回或设置段落中第一行之前的空间量（无继承）。 |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | 返回或设置段落中第一行之前的空间量（无继承）。 |
| [getSpaceAfter()](#getSpaceAfter--) | 返回或设置段落中最后一行之后的空间量（无继承）。 |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | 返回或设置段落中最后一行之后的空间量（无继承）。 |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | 确定段落中是否使用东亚换行符。 |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | 确定段落中是否使用东亚换行符。 |
| [getRightToLeft()](#getRightToLeft--) | 确定段落中是否使用从右到左的书写方式。 |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | 确定段落中是否使用从右到左的书写方式。 |
| [getLatinLineBreak()](#getLatinLineBreak--) | 确定段落中是否使用拉丁换行符。 |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | 确定段落中是否使用拉丁换行符。 |
| [getHangingPunctuation()](#getHangingPunctuation--) | 确定段落中是否使用悬挂标点。 |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | 确定段落中是否使用悬挂标点。 |
| [getMarginLeft()](#getMarginLeft--) | 返回或设置段落中左边距（无继承）。 |
| [setMarginLeft(float value)](#setMarginLeft-float-) | 返回或设置段落中左边距（无继承）。 |
| [getMarginRight()](#getMarginRight--) | 返回或设置段落中右边距（无继承）。 |
| [setMarginRight(float value)](#setMarginRight-float-) | 返回或设置段落中右边距（无继承）。 |
| [getIndent()](#getIndent--) | 返回或设置段落的首行缩进/悬挂缩进（无继承）。 |
| [setIndent(float value)](#setIndent-float-) | 返回或设置段落的首行缩进/悬挂缩进（无继承）。 |
| [getDefaultTabSize()](#getDefaultTabSize--) | 返回或设置默认制表符大小（无继承）。 |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | 返回或设置默认制表符大小（无继承）。 |
| [getTabs()](#getTabs--) | 返回段落的制表设置。 |
| [getFontAlignment()](#getFontAlignment--) | 返回或设置段落中不使用继承的字体对齐方式。 |
| [setFontAlignment(int value)](#setFontAlignment-int-) | 返回或设置段落中不使用继承的字体对齐方式。 |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | 返回段落的默认部分格式。 |
| [getEffective()](#getEffective--) | 获取已应用继承的有效段落格式数据。 |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

返回段落的项目符号格式。只读 [IBulletFormat](../../com.aspose.slides/ibulletformat)。

**返回:**  
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

返回或设置段落的深度。值 0 表示未定义值。读写 short。

**返回:**  
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

返回或设置段落的深度。值 0 表示未定义值。读写 short。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

返回或设置段落中不使用继承的文本对齐方式。读写 [TextAlignment](../../com.aspose.slides/textalignment)。

**返回:**  
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

返回或设置段落中不使用继承的文本对齐方式。读写 [TextAlignment](../../com.aspose.slides/textalignment)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

返回或设置段落中基线之间的空间量。正值表示百分比，负值表示点数大小。未应用继承。读写 float。

**返回:**  
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

返回或设置段落中基线之间的空间量。正值表示百分比，负值表示点数大小。未应用继承。读写 float。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

返回或设置段落中第一行之前的空间量（无继承）。正值指定空白空间应为字体大小的百分比。负值指定空白空间的点大小。读写 float。

**返回:**  
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

返回或设置段落中第一行之前的空间量（无继承）。正值指定空白空间应为字体大小的百分比。负值指定空白空间的点大小。读写 float。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

返回或设置段落中最后一行之后的空间量（无继承）。正值指定空白空间应为字体大小的百分比。负值指定空白空间的点大小。读写 float。

**返回:**  
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

返回或设置段落中最后一行之后的空间量（无继承）。正值指定空白空间应为字体大小的百分比。负值指定空白空间的点大小。读写 float。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

确定段落中是否使用东亚换行符。未应用继承。读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回:**  
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

确定段落中是否使用东亚换行符。未应用继承。读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

确定段落中是否使用从右到左的书写方式。未应用继承。读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回:**  
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

确定段落中是否使用从右到左的书写方式。未应用继承。读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

确定段落中是否使用拉丁换行符。未应用继承。读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回:**  
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

确定段落中是否使用拉丁换行符。未应用继承。读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

确定段落中是否使用悬挂标点。未应用继承。读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回:**  
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

确定段落中是否使用悬挂标点。未应用继承。读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

返回或设置段落中左边距（无继承）。读写 float。

**返回:**  
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

返回或设置段落中左边距（无继承）。读写 float。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

返回或设置段落中右边距（无继承）。读写 float。

**返回:**  
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

返回或设置段落中右边距（无继承）。读写 float。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

返回或设置段落的首行缩进/悬挂缩进（无继承）。悬挂缩进可用负值定义。读写 float。

**返回:**  
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

返回或设置段落的首行缩进/悬挂缩进（无继承）。悬挂缩进可用负值定义。读写 float。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

返回或设置默认制表符大小（无继承）。读写 float。

**返回:**  
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

返回或设置默认制表符大小（无继承）。读写 float。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

返回段落的制表设置。未应用继承。只读 [ITabCollection](../../com.aspose.slides/itabcollection)。

**返回:**  
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

返回或设置段落中不使用继承的字体对齐方式。读写 [FontAlignment](../../com.aspose.slides/fontalignment)。

**返回:**  
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

返回或设置段落中不使用继承的字体对齐方式。读写 [FontAlignment](../../com.aspose.slides/fontalignment)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

返回段落的默认部分格式。未应用继承。只读 [IPortionFormat](../../com.aspose.slides/iportionformat)。

**返回:**  
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

获取已应用继承的有效段落格式数据。

**返回:**  
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).