---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: 不可变对象，包含有效的文本框格式属性。
type: docs
url: /zh/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

不可变对象，包含有效的文本框格式属性。

--------------------

此接口与 [ITextFrameFormat](../../com.aspose.slides/itextframeformat) 接口一起使用，以返回应用继承后的有效格式化值。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | 返回有效文本的样式。 |
| [getMarginLeft()](#getMarginLeft--) | 返回 TextFrame 中的左边距（点）。 |
| [getMarginRight()](#getMarginRight--) | 返回 TextFrame 中的右边距（点）。 |
| [getMarginTop()](#getMarginTop--) | 返回 TextFrame 中的上边距（点）。 |
| [getMarginBottom()](#getMarginBottom--) | 返回 TextFrame 中的下边距（点）。 |
| [getWrapText()](#getWrapText--) | 返回文本是否在 TextFrame 的边距处换行。 |
| [getAnchoringType()](#getAnchoringType--) | 返回 TextFrame 中的垂直锚点文本。 |
| [getCenterText()](#getCenterText--) | 返回文本是否应在盒子中水平居中。 |
| [getTextVerticalType()](#getTextVerticalType--) | 返回文本方向。 |
| [getAutofitType()](#getAutofitType--) | 返回文本自动适配模式。 |
| [getColumnCount()](#getColumnCount--) | 指定边界矩形中文本的列数。 |
| [getColumnSpacing()](#getColumnSpacing--) | 指定文本区域中文本列之间的间距（以点为单位）。 |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```


返回有效文本的样式。只读 [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)。

**返回:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


返回 TextFrame 中的左边距（点）。只读 double。

**返回:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


返回 TextFrame 中的右边距（点）。只读 double。

**返回:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


返回 TextFrame 中的上边距（点）。只读 double。

**返回:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


返回 TextFrame 中的下边距（点）。只读 double。

**返回:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```


返回文本是否在 TextFrame 的边距处换行。只读 boolean。

**返回:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


返回 TextFrame 中的垂直锚点文本。只读 [TextAnchorType](../../com.aspose.slides/textanchortype)。

**返回:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```


返回文本是否应在盒子中水平居中。只读 boolean。

**返回:**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


返回文本方向。只读 [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**返回:**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


返回文本自动适配模式。只读 [TextAutofitType](../../com.aspose.slides/textautofittype)。

**返回:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


指定边界矩形中文本的列数。只读 int。

**返回:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```


指定文本区域中文本列之间的间距（以点为单位）。只读 float。

**返回:**
float