---
title: IFillFormat
second_title: Aspose.Slides for Android via Java API 參考文件
description: 表示填充格式選項。
type: docs
url: /zh-hant/com.aspose.slides/ifillformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

表示填充格式選項。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getFillType()](#getFillType--) | 返回或設定填充類型。 |
| [setFillType(byte value)](#setFillType-byte-) | 返回或設定填充類型。 |
| [getSolidFillColor()](#getSolidFillColor--) | 返回填充顏色。 |
| [getGradientFormat()](#getGradientFormat--) | 返回漸層填充格式。 |
| [getPatternFormat()](#getPatternFormat--) | 返回圖案填充格式。 |
| [getPictureFillFormat()](#getPictureFillFormat--) | 返回圖片填充格式。 |
| [getRotateWithShape()](#getRotateWithShape--) | 判斷填充是否應隨形狀旋轉。 |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | 判斷填充是否應隨形狀旋轉。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效填充格式資料。 |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

返回或設定填充的類型。讀寫 [FillType](../../com.aspose.slides/filltype)。

**返回值：**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

返回或設定填充的類型。讀寫 [FillType](../../com.aspose.slides/filltype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

返回填充顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回值：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

返回漸層填充格式。唯讀 [IGradientFormat](../../com.aspose.slides/igradientformat)。

**返回值：**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

返回圖案填充格式。唯讀 [IPatternFormat](../../com.aspose.slides/ipatternformat)。

**返回值：**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```

返回圖片填充格式。唯讀 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**返回值：**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

判斷填充是否應隨形狀旋轉。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回值：**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

判斷填充是否應隨形狀旋轉。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```

取得套用繼承後的有效填充格式資料。

**返回值：**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - 一個 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).