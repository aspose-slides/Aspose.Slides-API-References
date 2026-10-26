---
title: IBackground
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示投影片的背景。
type: docs
url: /zh-hant/com.aspose.slides/ibackground/
---
**全部已實作介面：**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

表示投影片的背景。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getType()](#getType--) | 傳回背景填充的類型。 |
| [setType(byte value)](#setType-byte-) | 傳回背景填充的類型。 |
| [getFillFormat()](#getFillFormat--) | 傳回 BackgroundType.OwnBackground 填充的 FillFormat。 |
| [getEffectFormat()](#getEffectFormat--) | 傳回 BackgroundType.OwnBackground 填充的 EffectFormat。 |
| [getStyleColor()](#getStyleColor--) | 傳回 BackgroundType.Themed 填充的 ColorFormat。 |
| [getStyleIndex()](#getStyleIndex--) | 傳回背景主題集合中 BackgroundType.Themed 填充的索引。 |
| [setStyleIndex(int value)](#setStyleIndex-int-) | 傳回背景主題集合中 BackgroundType.Themed 填充的索引。 |
| [getEffective()](#getEffective--) | 取得已套用繼承的有效背景資料。 |
### getType() {#getType--}
```
public abstract byte getType()
```

傳回背景填充的類型。 讀寫 [BackgroundType](../../com.aspose.slides/backgroundtype)。

**傳回：**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

傳回背景填充的類型。 讀寫 [BackgroundType](../../com.aspose.slides/backgroundtype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

傳回 BackgroundType.OwnBackground 填充的 FillFormat。 唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

**傳回：**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

傳回 BackgroundType.OwnBackground 填充的 EffectFormat。 唯讀 [IEffectFormat](../../com.aspose.slides/ieffectformat)。

**傳回：**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```

傳回 BackgroundType.Themed 填充的 ColorFormat。 唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**傳回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```

傳回背景主題集合中 BackgroundType.Themed 填充的索引。 0 代表無填充。1..999 為索引。 讀寫 int。

**傳回：**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```

傳回背景主題集合中 BackgroundType.Themed 填充的索引。 0 代表無填充。1..999 為索引。 讀寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```

取得已套用繼承的有效背景資料。

**傳回：**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - 一個 [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata)。