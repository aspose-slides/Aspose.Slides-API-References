---
title: IShapeStyle
second_title: Aspose.Slides for Android via Java API Reference
description: 表示形狀樣式參考。
type: docs
url: /zh-hant/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
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
| [getFontCollectionIndex()](#getFontCollectionIndex--) | 傳回或設定字型集合中形狀的字型索引。 |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | 傳回或設定字型集合中形狀的字型索引。 |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

傳回形狀的輪廓顏色。 唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**傳回值:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

傳回或設定樣式矩陣中線條的欄位索引。 可讀寫 int。

**傳回值:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

傳回或設定樣式矩陣中線條的欄位索引。 可讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

傳回形狀的填充顏色。 唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**傳回值:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

傳回或設定樣式矩陣中形狀的填充欄位索引。 0 代表無填充，正值為佈景主題的填充樣式索引，負值為佈景主題的背景樣式索引。 可讀寫 short。

**傳回值:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

傳回或設定樣式矩陣中形狀的填充欄位索引。 0 代表無填充，正值為佈景主題的填充樣式索引，負值為佈景主題的背景樣式索引。 可讀寫 short。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

傳回形狀的效果顏色。 唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**傳回值:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

傳回或設定樣式矩陣中形狀的效果欄位索引。 可讀寫 long。

**傳回值:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

傳回或設定樣式矩陣中形狀的效果欄位索引。 可讀寫 long。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

傳回形狀的字型顏色。 唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**傳回值:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

傳回或設定字型集合中形狀的字型索引。 可讀寫 [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)。

**傳回值:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

傳回或設定字型集合中形狀的字型索引。 可讀寫 [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |