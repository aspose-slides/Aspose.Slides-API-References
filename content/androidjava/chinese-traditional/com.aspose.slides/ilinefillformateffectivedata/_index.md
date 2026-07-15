---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 不可變物件，包含有效的行填充屬性。
type: docs
url: /zh-hant/com.aspose.slides/ilinefillformateffectivedata/
---
**所有已實作介面：**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

不可變物件，包含有效的行填充屬性。

--------------------

此介面作為 [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) 的一部分使用。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getFillType()](#getFillType--) | 返回填充類型。 |
| [getSolidFillColor()](#getSolidFillColor--) | 返回實心填充的顏色。 |
| [getGradientFormat()](#getGradientFormat--) | 返回漸層填充格式。 |
| [getPatternFormat()](#getPatternFormat--) | 返回圖案填充格式。 |
| [getRotateWithShape()](#getRotateWithShape--) | 判斷填充是否應隨形狀旋轉。 |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

返回填充類型。 唯讀 [FillType](../../com.aspose.slides/filltype)。

**返回：**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```

返回實心填充的顏色。 唯讀 java.lang.Integer。

**返回：**
java.lang.Integer
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

返回漸層填充格式。 唯讀 [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)。

**返回：**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

返回圖案填充格式。 唯讀 [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)。

**返回：**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

判斷填充是否應隨形狀旋轉。 唯讀 boolean。

**返回：**
boolean