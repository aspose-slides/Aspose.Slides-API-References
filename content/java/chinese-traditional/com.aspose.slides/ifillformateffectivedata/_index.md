---
title: IFillFormatEffectiveData
second_title: Aspose.Slides for Java API 參考
description: 不可變物件，包含有效的填充格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/ifillformateffectivedata/
---
**所有已實作的介面：**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

不可變物件，包含有效的填充格式屬性。

--------------------

此介面與 [IFillFormat](../../com.aspose.slides/ifillformat) 介面一起使用，以返回套用了繼承的有效格式值。

## 方法

| Method | Description |
| --- | --- |
| [getFillType()](#getFillType--) | 回傳填充類型。 |
| [getSolidFillColor()](#getSolidFillColor--) | 回傳填充顏色。 |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | 取得由色彩配置定義的填充顏色。 |
| [getGradientFormat()](#getGradientFormat--) | 回傳漸層填充格式。 |
| [getPatternFormat()](#getPatternFormat--) | 回傳圖樣填充格式。 |
| [getPictureFillFormat()](#getPictureFillFormat--) | 回傳圖片填充格式。 |
| [getRotateWithShape()](#getRotateWithShape--) | 判斷填充是否應隨形狀旋轉。 |

### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

回傳填充類型。唯讀 [FillType](../../com.aspose.slides/filltype)。

**回傳：**
byte

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```

回傳填充顏色。唯讀 java.awt.Color。

**回傳：**
java.awt.Color

### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```

取得由色彩配置定義的填充顏色。[SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) 值表示 SolidFillColor (\#getSolidFillColor.getSolidFillColor) 不是方案色。唯讀 [SchemeColor](../../com.aspose.slides/schemecolor)。

**回傳：**
int

### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

回傳漸層填充格式。唯讀 [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)。

**回傳：**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)

### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

回傳圖樣填充格式。唯讀 [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)。

**回傳：**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)

### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```

回傳圖片填充格式。唯讀 [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)。

**回傳：**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)

### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

判斷填充是否應隨形狀旋轉。唯讀 boolean。

**回傳：**
boolean