---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective text frame formatting properties.
type: docs
url: /zh-hant/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

不可變物件，包含有效文字框格式屬性。

--------------------

此介面與 [ITextFrameFormat](../../com.aspose.slides/itextframeformat) 介面一起使用，以返回套用繼承後的有效格式值。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | 返回有效文字的樣式。 |
| [getMarginLeft()](#getMarginLeft--) | 返回 TextFrame 中左側邊距（點）。 |
| [getMarginRight()](#getMarginRight--) | 返回 TextFrame 中右側邊距（點）。 |
| [getMarginTop()](#getMarginTop--) | 返回 TextFrame 中上側邊距（點）。 |
| [getMarginBottom()](#getMarginBottom--) | 返回 TextFrame 中下側邊距（點）。 |
| [getWrapText()](#getWrapText--) | 返回文字是否在 TextFrame 的邊距處換行。 |
| [getAnchoringType()](#getAnchoringType--) | 返回 TextFrame 中垂直錨點文字。 |
| [getCenterText()](#getCenterText--) | 返回文字是否應在框內水平置中。 |
| [getTextVerticalType()](#getTextVerticalType--) | 返回文字方向。 |
| [getAutofitType()](#getAutofitType--) | 返回文字自動調整模式。 |
| [getColumnCount()](#getColumnCount--) | 指定限定矩形中文字的欄位數。 |
| [getColumnSpacing()](#getColumnSpacing--) | 指定文字區域中欄位之間的間距（點）。 |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```


返回有效文字的樣式。唯讀 [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)。

**返回:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


返回 TextFrame 中左側邊距（點）。唯讀 double。

**返回:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


返回 TextFrame 中右側邊距（點）。唯讀 double。

**返回:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


返回 TextFrame 中上側邊距（點）。唯讀 double。

**返回:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


返回 TextFrame 中下側邊距（點）。唯讀 double。

**返回:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```


返回文字是否在 TextFrame 的邊距處換行。唯讀 boolean。

**返回:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


返回 TextFrame 中垂直錨點文字。唯讀 [TextAnchorType](../../com.aspose.slides/textanchortype)。

**返回:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```


返回文字是否應在框內水平置中。唯讀 boolean。

**返回:**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


返回文字方向。唯讀 [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**返回:**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


返回文字自動調整模式。唯讀 [TextAutofitType](../../com.aspose.slides/textautofittype)。

**返回:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


指定限定矩形中文字的欄位數。唯讀 int。

**返回:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```


指定文字區域中欄位之間的間距（點）。唯讀 float。

**返回:**
float