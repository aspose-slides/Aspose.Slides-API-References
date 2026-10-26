---
title: IGradientStop
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงรูปแบบการไล่สี
type: docs
url: /th/com.aspose.slides/igradientstop/
---```
public interface IGradientStop
```

แสดงรูปแบบการไล่สี.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPosition()](#getPosition--) | คืนค่า หรือกำหนดตำแหน่ง (0..1) ของจุดไล่สี. |
| [setPosition(float value)](#setPosition-float-) | คืนค่า หรือกำหนดตำแหน่ง (0..1) ของจุดไล่สี. |
| [getColor()](#getColor--) | คืนค่าสีของจุดไล่สี. |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```


คืนค่า หรือกำหนดตำแหน่ง (0..1) ของจุดไล่สี. อ่าน/เขียน float.

**คืนค่า:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```


คืนค่า หรือกำหนดตำแหน่ง (0..1) ของจุดไล่สี. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


คืนค่าสีของจุดไล่สี. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)