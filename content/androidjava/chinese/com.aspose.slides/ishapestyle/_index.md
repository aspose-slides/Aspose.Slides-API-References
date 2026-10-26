---
title: IShapeStyle
second_title: Aspose.Slides for Android via Java API Reference
description: Represent shapes style reference.
type: docs
url: /zh/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

表示形状的样式引用。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLineColor()](#getLineColor--) | 返回形状的轮廓颜色。 |
| [getLineStyleIndex()](#getLineStyleIndex--) | 返回或设置线的列索引（在样式矩阵中）。 |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | 返回或设置线的列索引（在样式矩阵中）。 |
| [getFillColor()](#getFillColor--) | 返回形状的填充颜色。 |
| [getFillStyleIndex()](#getFillStyleIndex--) | 返回或设置形状的填充列索引（在样式矩阵中）。 |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | 返回或设置形状的填充列索引（在样式矩阵中）。 |
| [getEffectColor()](#getEffectColor--) | 返回形状的效果颜色。 |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | 返回或设置形状的效果列索引（在样式矩阵中）。 |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | 返回或设置形状的效果列索引（在样式矩阵中）。 |
| [getFontColor()](#getFontColor--) | 返回形状的字体颜色。 |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | 返回或设置形状的字体索引（在字体集合中）。 |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | 返回或设置形状的字体索引（在字体集合中）。 |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

返回形状的轮廓颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

返回或设置线的列索引（在样式矩阵中）。读/写 int。

**返回:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

返回或设置线的列索引（在样式矩阵中）。读/写 int。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

返回形状的填充颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

返回或设置形状的填充列索引（在样式矩阵中）。0 表示无填充，正值 - 表示主题填充样式的索引，负值 - 表示主题背景样式的索引。读/写 short。

**返回:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

返回或设置形状的填充列索引（在样式矩阵中）。0 表示无填充，正值 - 表示主题填充样式的索引，负值 - 表示主题背景样式的索引。读/写 short。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

返回形状的效果颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

返回或设置形状的效果列索引（在样式矩阵中）。读/写 long。

**返回:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

返回或设置形状的效果列索引（在样式矩阵中）。读/写 long。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

返回形状的字体颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

返回或设置形状的字体索引（在字体集合中）。读/写 [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)。

**返回:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

返回或设置形状的字体索引（在字体集合中）。读/写 [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |