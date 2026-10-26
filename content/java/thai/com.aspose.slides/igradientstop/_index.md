---
title: IGradientStop
second_title: Aspose.Slides for Java API Reference
description: เป็นรูปแบบการไล่ระดับสี.
type: docs
url: /th/com.aspose.slides/igradientstop/
---```
public interface IGradientStop
```

เป็นรูปแบบการไล่ระดับสี.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPosition()](#getPosition--) | คืนค่า หรือกำหนดตำแหน่ง (0..1) ของจุดไล่ระดับสี. |
| [setPosition(float value)](#setPosition-float-) | คืนค่า หรือกำหนดตำแหน่ง (0..1) ของจุดไล่ระดับสี. |
| [getColor()](#getColor--) | คืนค่าสีของจุดไล่ระดับสี. |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```


คืนค่า หรือกำหนดตำแหน่ง (0..1) ของจุดไล่ระดับสี. อ่าน/เขียน float.

**คืนค่า:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```


คืนค่า หรือกำหนดตำแหน่ง (0..1) ของจุดไล่ระดับสี. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


คืนค่าสีของจุดไล่ระดับสี. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)