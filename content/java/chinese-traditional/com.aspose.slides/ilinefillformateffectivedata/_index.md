---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides for Java API 參考文件
description: 不可變物件，包含有效的線條填充屬性。
type: docs
url: /zh-hant/com.aspose.slides/ilinefillformateffectivedata/
---
**所有已實作的介面：**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

不可變物件，包含有效的線條填充屬性。

--------------------

此介面作為 [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) 的一部分使用。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getFillType()](#getFillType--) | 傳回填充類型。 |
| [getSolidFillColor()](#getSolidFillColor--) | 傳回實心填充的顏色。 |
| [getGradientFormat()](#getGradientFormat--) | 傳回漸層填充格式。 |
| [getPatternFormat()](#getPatternFormat--) | 傳回圖案填充格式。 |
| [getRotateWithShape()](#getRotateWithShape--) | 判斷填充是否應隨形狀旋轉。 |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


傳回填充類型。唯讀 [FillType](../../com.aspose.slides/filltype)。

**傳回：**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```


傳回實心填充的顏色。唯讀 java.awt.Color。

**傳回：**
java.awt.Color
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


傳回漸層填充格式。唯讀 [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)。

**傳回：**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


傳回圖案填充格式。唯讀 [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)。

**傳回：**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


判斷填充是否應隨形狀旋轉。唯讀 boolean。

**傳回：**
boolean