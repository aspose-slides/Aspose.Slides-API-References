---
title: ShapeStyle
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 表示形状样式引用。
type: docs
url: /zh/com.aspose.slides/shapestyle/
---
**继承：**
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口：**
[com.aspose.slides.IShapeStyle](../../com.aspose.slides/ishapestyle)
```
public class ShapeStyle extends DomObject<Shape> implements IShapeStyle
```

表示形状的样式引用。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getLineColor()](#getLineColor--) | 返回形状的轮廓颜色。 |
| [getLineStyleIndex()](#getLineStyleIndex--) | 返回或设置线条在样式矩阵中的列索引。 |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | 返回或设置线条在样式矩阵中的列索引。 |
| [getFillColor()](#getFillColor--) | 返回形状的填充颜色。 |
| [getFillStyleIndex()](#getFillStyleIndex--) | 返回或设置形状在样式矩阵中的填充列索引。 |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | 返回或设置形状在样式矩阵中的填充列索引。 |
| [getEffectColor()](#getEffectColor--) | 返回形状的效果颜色。 |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | 返回或设置形状在样式矩阵中的效果列索引。 |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | 返回或设置形状在样式矩阵中的效果列索引。 |
| [getFontColor()](#getFontColor--) | 返回形状的字体颜色。 |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | 返回或设置形状在字体集合中的字体索引。 |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | 返回或设置形状在字体集合中的字体索引。 |

### getLineColor() {#getLineColor--}
```
public final IColorFormat getLineColor()
```

返回形状的轮廓颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat).

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getLineStyleIndex() {#getLineStyleIndex--}
```
public final int getLineStyleIndex()
```

返回或设置线条在样式矩阵中的列索引。读写 int.

**返回：**
int

### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public final void setLineStyleIndex(int value)
```

返回或设置线条在样式矩阵中的列索引。读写 int.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFillColor() {#getFillColor--}
```
public final IColorFormat getFillColor()
```

返回形状的填充颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat).

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getFillStyleIndex() {#getFillStyleIndex--}
```
public final short getFillStyleIndex()
```

返回或设置形状在样式矩阵中的填充列索引。0 表示无填充，正值表示主题填充样式的索引，负值表示主题背景样式的索引。读写 short。

**返回：**
short

### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public final void setFillStyleIndex(short value)
```

返回或设置形状在样式矩阵中的填充列索引。0 表示无填充，正值表示主题填充样式的索引，负值表示主题背景样式的索引。读写 short。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getEffectColor() {#getEffectColor--}
```
public final IColorFormat getEffectColor()
```

返回形状的效果颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat).

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public final long getEffectStyleIndex()
```

返回或设置形状在样式矩阵中的效果列索引。读写 long。

**返回：**
long

### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public final void setEffectStyleIndex(long value)
```

返回或设置形状在样式矩阵中的效果列索引。读写 long。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getFontColor() {#getFontColor--}
```
public final IColorFormat getFontColor()
```

返回形状的字体颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat).

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public final byte getFontCollectionIndex()
```

返回或设置形状在字体集合中的字体索引。读写 [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)。

**返回：**
byte

### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public final void setFontCollectionIndex(byte value)
```

返回或设置形状在字体集合中的字体索引。读写 [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |