---
title: IShapeStyle
second_title: Aspose.Slides for Java API Reference
description: Represent shapes style reference.
type: docs
url: /zh-hant/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

表示形狀的樣式參考。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getLineColor()](#getLineColor--) | 返回形狀的外框顏色。 |
| [getLineStyleIndex()](#getLineStyleIndex--) | 返回或設定線條在樣式矩陣中的欄索引。 |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | 返回或設定線條在樣式矩陣中的欄索引。 |
| [getFillColor()](#getFillColor--) | 返回形狀的填充顏色。 |
| [getFillStyleIndex()](#getFillStyleIndex--) | 返回或設定形狀在樣式矩陣中的填充欄索引。 |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | 返回或設定形狀在樣式矩陣中的填充欄索引。 |
| [getEffectColor()](#getEffectColor--) | 返回形狀的效果顏色。 |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | 返回或設定形狀在樣式矩陣中的效果欄索引。 |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | 返回或設定形狀在樣式矩陣中的效果欄索引。 |
| [getFontColor()](#getFontColor--) | 返回形狀的字體顏色。 |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | 返回或設定形狀在字體集合中的字體索引。 |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | 返回或設定形狀在字體集合中的字體索引。 |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

返回形狀的外框顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

返回或設定線條在樣式矩陣中的欄索引。讀寫 int。

**返回：**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

返回或設定線條在樣式矩陣中的欄索引。讀寫 int。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

返回形狀的填充顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

返回或設定形狀在樣式矩陣中的填充欄索引。0 表示無填充，正值為主題填充樣式的索引，負值為主題背景樣式的索引。讀寫 short。

**返回：**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

返回或設定形狀在樣式矩陣中的填充欄索引。0 表示無填充，正值為主題填充樣式的索引，負值為主題背景樣式的索引。讀寫 short。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

返回形狀的效果顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

返回或設定形狀在樣式矩陣中的效果欄索引。讀寫 long。

**返回：**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

返回或設定形狀在樣式矩陣中的效果欄索引。讀寫 long。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

返回形狀的字體顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

返回或設定形狀在字體集合中的字體索引。讀寫 [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)。

**返回：**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

返回或設定形狀在字體集合中的字體索引。讀寫 [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | byte |  |