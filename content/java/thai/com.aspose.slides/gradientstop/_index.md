---
title: GradientStop
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นรูปแบบการไล่สี.
type: docs
url: /th/com.aspose.slides/gradientstop/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**  
[com.aspose.slides.IGradientStop](../../com.aspose.slides/igradientstop)
```
public final class GradientStop extends PVIObject implements IGradientStop
```

Represents a gradient format.  
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | ส่งคืนหรือกำหนดตำแหน่ง (0..1) ของจุดไล่สี. |
| [setPosition(float value)](#setPosition-float-) | ส่งคืนหรือกำหนดตำแหน่ง (0..1) ของจุดไล่สี. |
| [getColor()](#getColor--) | ส่งคืนสีของจุดไล่สี. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. อ่านอย่างเดียว long.

**Returns:**  
long
### getPosition() {#getPosition--}
```
public final float getPosition()
```

ส่งคืนหรือกำหนดตำแหน่ง (0..1) ของจุดไล่สี. อ่าน/เขียน  float .

**Returns:**  
float
### setPosition(float value) {#setPosition-float-}
```
public final void setPosition(float value)
```

ส่งคืนหรือกำหนดตำแหน่ง (0..1) ของจุดไล่สี. อ่าน/เขียน  float .

**Parameters:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

ส่งคืนสีของจุดไล่สี. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**  
[IColorFormat](../../com.aspose.slides/icolorformat)