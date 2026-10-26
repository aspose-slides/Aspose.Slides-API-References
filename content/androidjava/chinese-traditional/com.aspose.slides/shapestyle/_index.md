---
title: ShapeStyle
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示形狀的樣式參考。
type: docs
url: /zh-hant/com.aspose.slides/shapestyle/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面：**
[com.aspose.slides.IShapeStyle](../../com.aspose.slides/ishapestyle)
```
public class ShapeStyle extends DomObject<Shape> implements IShapeStyle
```

表示形狀的樣式參考。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getLineColor()](#getLineColor--) | 傳回形狀的輪廓顏色。 |
| [getLineStyleIndex()](#getLineStyleIndex--) | 傳回或設定樣式矩陣中線條的欄位索引。 |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | 傳回或設定樣式矩陣中線條的欄位索引。 |
| [getFillColor()](#getFillColor--) | 傳回形狀的填充顏色。 |
| [getFillStyleIndex()](#getFillStyleIndex--) | 傳回或設定樣式矩陣中形狀的填充欄位索引。 |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | 傳回或設定樣式矩陣中形狀的填充欄位索引。 |
| [getEffectColor()](#getEffectColor--) | 傳回形狀的效果顏色。 |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | 傳回或設定樣式矩陣中形狀的效果欄位索引。 |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | 傳回或設定樣式矩陣中形狀的效果欄位索引。 |
| [getFontColor()](#getFontColor--) | 傳回形狀的字型顏色。 |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | 傳回或設定形狀在字型集合中的字型索引。 |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | 傳回或設定形狀在字型集合中的字型索引。 |
### getLineColor() {#getLineColor--}
```
public final IColorFormat getLineColor()
```

傳回形狀的輪廓顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回值：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public final int getLineStyleIndex()
```

傳回或設定樣式矩陣中線條的欄位索引。讀寫 int。

**返回值：**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public final void setLineStyleIndex(int value)
```

傳回或設定樣式矩陣中線條的欄位索引。讀寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public final IColorFormat getFillColor()
```

傳回形狀的填充顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回值：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public final short getFillStyleIndex()
```

傳回或設定樣式矩陣中形狀的填充欄位索引。0 表示無填充，正值 - 主題填充樣式的索引，負值 - 主題背景樣式的索引。讀寫 short。

**返回值：**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public final void setFillStyleIndex(short value)
```

傳回或設定樣式矩陣中形狀的填充欄位索引。0 表示無填充，正值 - 主題填充樣式的索引，負值 - 主題背景樣式的索引。讀寫 short。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public final IColorFormat getEffectColor()
```

傳回形狀的效果顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回值：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public final long getEffectStyleIndex()
```

傳回或設定樣式矩陣中形狀的效果欄位索引。讀寫 long。

**返回值：**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public final void setEffectStyleIndex(long value)
```

傳回或設定樣式矩陣中形狀的效果欄位索引。讀寫 long。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public final IColorFormat getFontColor()
```

傳回形狀的字型顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回值：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public final byte getFontCollectionIndex()
```

傳回或設定形狀在字型集合中的字型索引。讀寫 [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)。

**返回值：**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public final void setFontCollectionIndex(byte value)
```

傳回或設定形狀在字型集合中的字型索引。讀寫 [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |