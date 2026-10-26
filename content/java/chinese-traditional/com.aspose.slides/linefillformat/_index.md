---
title: LineFillFormat
second_title: Aspose.Slides for Java API 參考
description: 表示線條填充的屬性。
type: docs
url: /zh-hant/com.aspose.slides/linefillformat/
---
**繼承關係:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**全部已實作介面:**
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

表示線條填充的屬性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | 返回或設定填充類型。 |
| [setFillType(byte value)](#setFillType-byte-) | 返回或設定填充類型。 |
| [getRotateWithShape()](#getRotateWithShape--) | 判斷填充是否應隨形狀旋轉。 |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | 判斷填充是否應隨形狀旋轉。 |
| [getSolidFillColor()](#getSolidFillColor--) | 返回實心填充的顏色。 |
| [getGradientFormat()](#getGradientFormat--) | 返回漸層填充格式。 |
| [getPatternFormat()](#getPatternFormat--) | 返回圖案填充格式。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long.

**傳回值:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```

返回或設定填充類型。可讀寫 [FillType](../../com.aspose.slides/filltype)。

**傳回值:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

返回或設定填充類型。可讀寫 [FillType](../../com.aspose.slides/filltype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

判斷填充是否應隨形狀旋轉。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回值:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

判斷填充是否應隨形狀旋轉。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

返回實心填充的顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**傳回值:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

返回漸層填充格式。唯讀 [IGradientFormat](../../com.aspose.slides/igradientformat)。

**傳回值:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

返回圖案填充格式。唯讀 [IPatternFormat](../../com.aspose.slides/ipatternformat)。

**傳回值:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)