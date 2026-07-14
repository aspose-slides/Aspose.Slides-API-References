---
title: GradientStop
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงรูปแบบไล่สี.
type: docs
url: /th/com.aspose.slides/gradientstop/
---
**สืบทอด:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.IGradientStop](../../com.aspose.slides/igradientstop)
```
public final class GradientStop extends PVIObject implements IGradientStop
```

แสดงถึงรูปแบบไล่สี.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | คืนค่า หรือกำหนดตำแหน่ง (0..1) ของจุดไล่สี. |
| [setPosition(float value)](#setPosition-float-) | คืนค่า หรือกำหนดตำแหน่ง (0..1) ของจุดไล่สี. |
| [getColor()](#getColor--) | คืนค่าสีของจุดไล่สี. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**  
long
### getPosition() {#getPosition--}
```
public final float getPosition()
```


คืนค่า หรือกำหนดตำแหน่ง (0..1) ของจุดไล่สี. อ่าน/เขียน  float .

**คืนค่า:**  
float
### setPosition(float value) {#setPosition-float-}
```
public final void setPosition(float value)
```


คืนค่า หรือกำหนดตำแหน่ง (0..1) ของจุดไล่สี. อ่าน/เขียน  float .

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


คืนค่าสีของจุดไล่สี. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**  
[IColorFormat](../../com.aspose.slides/icolorformat)