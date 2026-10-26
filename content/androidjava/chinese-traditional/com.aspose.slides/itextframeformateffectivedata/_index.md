---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Android via Java API 參考文件
description: 此不可變物件包含有效的文字框格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

此不可變物件包含有效的文字框格式屬性。

--------------------

此介面與 [ITextFrameFormat](../../com.aspose.slides/itextframeformat) 介面共同使用，以回傳套用繼承的有效格式值。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | 回傳有效文字的樣式。 |
| [getMarginLeft()](#getMarginLeft--) | 回傳 TextFrame 中左邊距（點）。 |
| [getMarginRight()](#getMarginRight--) | 回傳 TextFrame 中右邊距（點）。 |
| [getMarginTop()](#getMarginTop--) | 回傳 TextFrame 中上邊距（點）。 |
| [getMarginBottom()](#getMarginBottom--) | 回傳 TextFrame 中下邊距（點）。 |
| [getWrapText()](#getWrapText--) | 回傳文字是否在 TextFrame 的邊距換行。 |
| [getAnchoringType()](#getAnchoringType--) | 回傳 TextFrame 中的垂直錨點文字。 |
| [getCenterText()](#getCenterText--) | 回傳文字是否應在盒子內水平置中。 |
| [getTextVerticalType()](#getTextVerticalType--) | 回傳文字方向。 |
| [getAutofitType()](#getAutofitType--) | 回傳文字自動調整模式。 |
| [getColumnCount()](#getColumnCount--) | 指定在邊界矩形內文字的欄數。 |
| [getColumnSpacing()](#getColumnSpacing--) | 指定文字區域中欄與欄之間的間距（點）。 |

### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```

回傳有效文字的樣式。只讀 [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)。

**返回：**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

回傳 TextFrame 中左邊距（點）。只讀 double。

**返回：**
double

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

回傳 TextFrame 中右邊距（點）。只讀 double。

**返回：**
double

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

回傳 TextFrame 中上邊距（點）。只讀 double。

**返回：**
double

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

回傳 TextFrame 中下邊距（點）。只讀 double。

**返回：**
double

### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```

回傳文字是否在 TextFrame 的邊距換行。只讀 boolean。

**返回：**
boolean

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

回傳 TextFrame 中的垂直錨點文字。只讀 [TextAnchorType](../../com.aspose.slides/textanchortype)。

**返回：**
byte

### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```

回傳文字是否應在盒子內水平置中。只讀 boolean。

**返回：**
boolean

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

回傳文字方向。只讀 [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**返回：**
byte

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

回傳文字自動調整模式。只讀 [TextAutofitType](../../com.aspose.slides/textautofittype)。

**返回：**
byte

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

指定在邊界矩形內文字的欄數。只讀 int。

**返回：**
int

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```

指定文字區域中欄與欄之間的間距（點）。只讀 float。

**返回：**
float