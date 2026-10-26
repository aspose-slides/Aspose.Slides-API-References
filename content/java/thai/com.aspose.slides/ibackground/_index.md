---
title: IBackground
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงพื้นหลังของสไลด์หนึ่ง.
type: docs
url: /th/com.aspose.slides/ibackground/
---
**ส่วนต่อประสานที่ใช้งานทั้งหมด:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

เป็นการแทนพื้นหลังของสไลด์หนึ่ง.
## วิธีการ

| Method | Description |
| --- | --- |
| [getType()](#getType--) | คืนค่าประเภทของการเติมพื้นหลัง. |
| [setType(byte value)](#setType-byte-) | คืนค่าประเภทของการเติมพื้นหลัง. |
| [getFillFormat()](#getFillFormat--) | คืนค่า FillFormat สำหรับการเติม BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | คืนค่า EffectFormat สำหรับการเติม BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | คืนค่า ColorFormat สำหรับการเติม BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | คืนดัชนีของการเติม BackgroundType.Themed ในคอลเลกชันธีมพื้นหลัง. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | คืนดัชนีของการเติม BackgroundType.Themed ในคอลเลกชันธีมพื้นหลัง. |
| [getEffective()](#getEffective--) | รับข้อมูลพื้นหลังที่มีผลโดยการสืบทอด. |
### getType() {#getType--}
```
public abstract byte getType()
```

คืนค่าประเภทของการเติมพื้นหลัง. อ่าน/เขียน [BackgroundType](../../com.aspose.slides/backgroundtype).

**คืนค่า:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

คืนค่าประเภทของการเติมพื้นหลัง. อ่าน/เขียน [BackgroundType](../../com.aspose.slides/backgroundtype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

คืนค่า FillFormat สำหรับการเติม BackgroundType.OwnBackground. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

คืนค่า EffectFormat สำหรับการเติม BackgroundType.OwnBackground. อ่านอย่างเดียว [IEffectFormat](../../com.aspose.slides/ieffectformat).

**คืนค่า:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```

คืนค่า ColorFormat สำหรับการเติม BackgroundType.Themed. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```

คืนดัชนีของการเติม BackgroundType.Themed ในคอลเลกชันธีมพื้นหลัง. 0 หมายถึงไม่มีการเติม. 1..999 - ดัชนี. อ่าน/เขียน int.

**คืนค่า:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```

คืนดัชนีของการเติม BackgroundType.Themed ในคอลเลกชันธีมพื้นหลัง. 0 หมายถึงไม่มีการเติม. 1..999 - ดัชนี. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```

รับข้อมูลพื้นหลังที่มีผลโดยการสืบทอด.

**คืนค่า:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).