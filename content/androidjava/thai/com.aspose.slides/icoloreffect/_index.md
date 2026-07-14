---
title: IColorEffect
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: แสดงถึงเอฟเฟกต์สีสำหรับพฤติกรรมการเคลื่อนไหว.
type: docs
url: /th/com.aspose.slides/icoloreffect/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IColorEffect extends IBehavior
```

แสดงถึงเอฟเฟกต์สีสำหรับพฤติกรรมการเคลื่อนไหว.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFrom()](#getFrom--) | ค่านี้ใช้เพื่อระบุสีเริ่มต้นของพฤติกรรม. |
| [setFrom(IColorFormat value)](#setFrom-com.aspose.slides.IColorFormat-) | ค่านี้ใช้เพื่อระบุสีเริ่มต้นของพฤติกรรม. |
| [getTo()](#getTo--) | อธิบายสีผลลัพธ์สำหรับการเปลี่ยนสีของการเคลื่อนไหว. |
| [setTo(IColorFormat value)](#setTo-com.aspose.slides.IColorFormat-) | อธิบายสีผลลัพธ์สำหรับการเปลี่ยนสีของการเคลื่อนไหว. |
| [getBy()](#getBy--) | อธิบายค่าการออฟเซ็ตสัมพันธ์สำหรับการเคลื่อนไหวสี. |
| [setBy(IColorOffset value)](#setBy-com.aspose.slides.IColorOffset-) | อธิบายค่าการออฟเซ็ตสัมพันธ์สำหรับการเคลื่อนไหวสี. |
| [getColorSpace()](#getColorSpace--) | แสดงถึงพื้นที่สีของพฤติกรรม. |
| [setColorSpace(int value)](#setColorSpace-int-) | แสดงถึงพื้นที่สีของพฤติกรรม. |
| [getDirection()](#getDirection--) | ระบุทิศทางที่วนสีตามวงล้อสี. |
| [setDirection(int value)](#setDirection-int-) | ระบุทิศทางที่วนสีตามวงล้อสี. |
### getFrom() {#getFrom--}
```
public abstract IColorFormat getFrom()
```

ค่านี้ใช้เพื่อระบุสีเริ่มต้นของพฤติกรรม. อ่าน/เขียน [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setFrom(IColorFormat value) {#setFrom-com.aspose.slides.IColorFormat-}
```
public abstract void setFrom(IColorFormat value)
```

ค่านี้ใช้เพื่อระบุสีเริ่มต้นของพฤติกรรม. อ่าน/เขียน [IColorFormat](../../com.aspose.slides/icolorformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getTo() {#getTo--}
```
public abstract IColorFormat getTo()
```

อธิบายสีผลลัพธ์สำหรับการเปลี่ยนสีของการเคลื่อนไหว. อ่าน/เขียน [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setTo(IColorFormat value) {#setTo-com.aspose.slides.IColorFormat-}
```
public abstract void setTo(IColorFormat value)
```

อธิบายสีผลลัพธ์สำหรับการเปลี่ยนสีของการเคลื่อนไหว. อ่าน/เขียน [IColorFormat](../../com.aspose.slides/icolorformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getBy() {#getBy--}
```
public abstract IColorOffset getBy()
```

อธิบายค่าการออฟเซ็ตสัมพันธ์สำหรับการเคลื่อนไหวสี. อ่าน/เขียน [IColorOffset](../../com.aspose.slides/icoloroffset).

**คืนค่า:**
[IColorOffset](../../com.aspose.slides/icoloroffset)
### setBy(IColorOffset value) {#setBy-com.aspose.slides.IColorOffset-}
```
public abstract void setBy(IColorOffset value)
```

อธิบายค่าการออฟเซ็ตสัมพันธ์สำหรับการเคลื่อนไหวสี. อ่าน/เขียน [IColorOffset](../../com.aspose.slides/icoloroffset).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IColorOffset](../../com.aspose.slides/icoloroffset) |  |
### getColorSpace() {#getColorSpace--}
```
public abstract int getColorSpace()
```

แสดงถึงพื้นที่สีของพฤติกรรม. อ่าน/เขียน [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**คืนค่า:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public abstract void setColorSpace(int value)
```

แสดงถึงพื้นที่สีของพฤติกรรม. อ่าน/เขียน [ColorSpace](../../com.aspose.slides/colorspace)(\#getColorSpace.getColorSpace/\#setColorSpace(int).setColorSpace(int)).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

ระบุทิศทางที่วนสีตามวงล้อสี. อ่าน/เขียน [ColorDirection](../../com.aspose.slides/colordirection).

**คืนค่า:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

ระบุทิศทางที่วนสีตามวงล้อสี. อ่าน/เขียน [ColorDirection](../../com.aspose.slides/colordirection).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |