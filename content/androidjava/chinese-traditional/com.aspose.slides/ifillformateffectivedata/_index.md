---
title: IFillFormatEffectiveData
second_title: Aspose.Slides for Android via Java API 參考
description: 不可變的物件，包含有效的填充格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/ifillformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

不可變的物件，包含有效的填充格式屬性。

--------------------

此介面與 [IFillFormat](../../com.aspose.slides/ifillformat) 介面共同使用，以在套用繼承後回傳有效的格式值。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFillType()](#getFillType--) | 返回填充的類型。 |
| [getSolidFillColor()](#getSolidFillColor--) | 返回填充顏色。 |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | 取得由顏色配置定義的填充顏色。 |
| [getGradientFormat()](#getGradientFormat--) | 返回漸層填充格式。 |
| [getPatternFormat()](#getPatternFormat--) | 返回圖案填充格式。 |
| [getPictureFillFormat()](#getPictureFillFormat--) | 返回圖片填充格式。 |
| [getRotateWithShape()](#getRotateWithShape--) | 判斷填充是否應隨形狀旋轉。 |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

返回填充的類型。唯讀 [FillType](../../com.aspose.slides/filltype)。

**返回：**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```

返回填充顏色。唯讀 java.lang.Integer。

**返回：**
java.lang.Integer
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```

取得由顏色配置定義的填充顏色。 [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) 值表示 SolidFillColor (\#getSolidFillColor.getSolidFillColor) 不是方案顏色。唯讀 [SchemeColor](../../com.aspose.slides/schemecolor)。

**返回：**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

返回漸層填充格式。唯讀 [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)。

**返回：**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

返回圖案填充格式。唯讀 [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)。

**返回：**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```

返回圖片填充格式。唯讀 [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)。

**返回：**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

判斷填充是否應隨形狀旋轉。唯讀 boolean。

**返回：**
boolean