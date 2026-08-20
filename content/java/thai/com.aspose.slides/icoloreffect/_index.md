---
title: IColorEffect
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงเอฟเฟ็กต์สีสำหรับพฤติกรรมแอนิเมชัน.
type: docs
url: /th/com.aspose.slides/icoloreffect/
---
**ส่วนต่อประสานที่ดำเนินการทั้งหมด:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IColorEffect extends IBehavior
```

แสดงถึงเอฟเฟ็กต์สีสำหรับพฤติกรรมแอนิเมชัน.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFrom()](#getFrom--) | ค่านี้ใช้เพื่อกำหนดสีเริ่มต้นของพฤติกรรม. |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | ค่านี้ใช้เพื่อกำหนดสีเริ่มต้นของพฤติกรรม. |
| [getTo()](#getTo--) | อธิบายสีที่ได้จากการเปลี่ยนสีของแอนิเมชัน. |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | อธิบายสีที่ได้จากการเปลี่ยนสีของแอนิเมชัน. |
| [getBy()](#getBy--) | อธิบายค่าการเยื้องเชิงสัมพัทธ์สำหรับแอนิเมชันสี. |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | อธิบายค่าการเยื้องเชิงสัมพัทธ์สำหรับแอนิเมชันสี. |
| [getColorSpace()](#getColorSpace--) | แสดงพื้นที่สีของพฤติกรรม. |
| [setColorSpace(int value)](#setColorSpace-int-) | แสดงพื้นที่สีของพฤติกรรม. |
| [getDirection()](#getDirection--) | ระบุทิศทางที่สีจะวนรอบวงล้อสี. |
| [setDirection(int value)](#setDirection-int-) | ระบุทิศทางที่สีจะวนรอบวงล้อสี. |
### getFrom() {#getFrom--}
```
public abstract IColorFormat getFrom()
```


ค่านี้ใช้เพื่อกำหนดสีเริ่มต้นของพฤติกรรม. อ่าน/เขียน [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public abstract void setFrom(IColorFormat value)
```


ค่านี้ใช้เพื่อกำหนดสีเริ่มต้นของพฤติกรรม. อ่าน/เขียน [IColorFormat](../../com.aspose.slides/icolorformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getTo() {#getTo--}
```
public abstract IColorFormat getTo()
```


อธิบายสีที่ได้จากการเปลี่ยนสีของแอนิเมชัน. อ่าน/เขียน [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public abstract void setTo(IColorFormat value)
```


อธิบายสีที่ได้จากการเปลี่ยนสีของแอนิเมชัน. อ่าน/เขียน [IColorFormat](../../com.aspose.slides/icolorformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### getBy() {#getBy--}
```
public abstract IColorOffset getBy()
```


อธิบายค่าการเยื้องเชิงสัมพัทธ์สำหรับแอนิเมชันสี. อ่าน/เขียน [IColorOffset](../../com.aspose.slides/icoloroffset).

**คืนค่า:**
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public abstract void setBy(IColorOffset value)
```


อธิบายค่าการเยื้องเชิงสัมพัทธ์สำหรับแอนิเมชันสี. อ่าน/เขียน [IColorOffset](../../com.aspose.slides/icoloroffset).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |

### getColorSpace() {#getColorSpace--}
```
public abstract int getColorSpace()
```


แสดงพื้นที่สีของพฤติกรรม. อ่าน/เขียน [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**คืนค่า:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public abstract void setColorSpace(int value)
```


แสดงพื้นที่สีของพฤติกรรม. อ่าน/เขียน [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


ระบุทิศทางที่สีจะวนรอบวงล้อสี. อ่าน/เขียน [ColorDirection](../../com.aspose.slides/colordirection).

**คืนค่า:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```


ระบุทิศทางที่สีจะวนรอบวงล้อสี. อ่าน/เขียน [ColorDirection](../../com.aspose.slides/colordirection).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |