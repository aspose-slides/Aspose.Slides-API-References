---
title: LineFillFormat
second_title: Aspose.Slides for Android via Java API 參考
description: 表示線條填充的屬性。
type: docs
url: /zh-hant/com.aspose.slides/linefillformat/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**已實作的介面:**  
[com.aspose.slides.ILineFillFormat](../../com.aspose.slides/ilinefillformat)
```
public final class LineFillFormat extends PVIObject implements ILineFillFormat
```

代表線條填充的屬性。

## 方法

| 方法 | 說明 |
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

版本。唯讀 long。

**返回:**  
long

### getFillType() {#getFillType--}
```
public final byte getFillType()
```

返回或設定填充類型。讀寫 [FillType](../../com.aspose.slides/filltype)。

**返回:**  
byte

### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

返回或設定填充類型。讀寫 [FillType](../../com.aspose.slides/filltype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

判斷填充是否應隨形狀旋轉。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回:**  
byte

### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

判斷填充是否應隨形狀旋轉。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

返回實心填充的顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

返回漸層填充格式。唯讀 [IGradientFormat](../../com.aspose.slides/igradientformat)。

**返回:**  
[IGradientFormat](../../com.aspose.slides/igradientformat)

### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

返回圖案填充格式。唯讀 [IPatternFormat](../../com.aspose.slides/ipatternformat)。

**返回:**  
[IPatternFormat](../../com.aspose.slides/ipatternformat)