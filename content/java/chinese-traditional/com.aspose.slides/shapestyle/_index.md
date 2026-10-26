---
title: ShapeStyle
second_title: Aspose.Slides for Java API 參考
description: 表示形狀樣式參考。
type: docs
url: /zh-hant/com.aspose.slides/shapestyle/
---
**繼承:**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面:**
[com.aspose.slides.IShapeStyle](../../com.aspose.slides/ishapestyle)
```
public class ShapeStyle extends DomObject<Shape> implements IShapeStyle
```

表示形狀的樣式參考。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLineColor()](#getLineColor--) | 返回形狀的輪廓顏色。 |
| [getLineStyleIndex()](#getLineStyleIndex--) | 返回或設定樣式矩陣中線條的欄索引。 |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | 返回或設定樣式矩陣中線條的欄索引。 |
| [getFillColor()](#getFillColor--) | 返回形狀的填充顏色。 |
| [getFillStyleIndex()](#getFillStyleIndex--) | 返回或設定樣式矩陣中形狀的填充欄索引。 |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | 返回或設定樣式矩陣中形狀的填充欄索引。 |
| [getEffectColor()](#getEffectColor--) | 返回形狀的效果顏色。 |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | 返回或設定樣式矩陣中形狀的效果欄索引。 |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | 返回或設定樣式矩陣中形狀的效果欄索引。 |
| [getFontColor()](#getFontColor--) | 返回形狀的字型顏色。 |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | 返回或設定字型集合中形狀的字型索引。 |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | 返回或設定字型集合中形狀的字型索引。 |
### getLineColor() {#getLineColor--}
```
public final IColorFormat getLineColor()
```

返回形狀的輪廓顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public final int getLineStyleIndex()
```

返回或設定樣式矩陣中線條的欄索引。可讀寫 int。

**返回：**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public final void setLineStyleIndex(int value)
```

返回或設定樣式矩陣中線條的欄索引。可讀寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public final IColorFormat getFillColor()
```

返回形狀的填充顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public final short getFillStyleIndex()
```

返回或設定樣式矩陣中形狀的填充欄索引。0 表示無填充，正值 - 主題填充樣式的索引，負值 - 主題背景樣式的索引。可讀寫 short。

**返回：**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public final void setFillStyleIndex(short value)
```

返回或設定樣式矩陣中形狀的填充欄索引。0 表示無填充，正值 - 主題填充樣式的索引，負值 - 主題背景樣式的索引。可讀寫 short。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public final IColorFormat getEffectColor()
```

返回形狀的效果顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public final long getEffectStyleIndex()
```

返回或設定樣式矩陣中形狀的效果欄索引。可讀寫 long。

**返回：**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public final void setEffectStyleIndex(long value)
```

返回或設定樣式矩陣中形狀的效果欄索引。可讀寫 long。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public final IColorFormat getFontColor()
```

返回形狀的字型顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public final byte getFontCollectionIndex()
```

返回或設定字型集合中形狀的字型索引。可讀寫 [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)。

**返回：**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public final void setFontCollectionIndex(byte value)
```

返回或設定字型集合中形狀的字型索引。可讀寫 [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |