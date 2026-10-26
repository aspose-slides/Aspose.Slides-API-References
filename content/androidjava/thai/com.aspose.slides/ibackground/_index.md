---
title: IBackground
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงพื้นหลังของสไลด์.
type: docs
url: /th/com.aspose.slides/ibackground/
---
**ทุก Interface ที่นำไปใช้:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

แสดงพื้นหลังของสไลด์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getType()](#getType--) | ส่งคืนประเภทของการเติมพื้นหลัง. |
| [setType(byte value)](#setType-byte-) | ส่งคืนประเภทของการเติมพื้นหลัง. |
| [getFillFormat()](#getFillFormat--) | ส่งคืน FillFormat สำหรับการเติม BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | ส่งคืน EffectFormat สำหรับการเติม BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | ส่งคืน ColorFormat สำหรับการเติม BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | ส่งคืนดัชนีของการเติม BackgroundType.Themed ในคอลเลกชันธีมพื้นหลัง. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | ส่งคืนดัชนีของการเติม BackgroundType.Themed ในคอลเลกชันธีมพื้นหลัง. |
| [getEffective()](#getEffective--) | รับข้อมูลพื้นหลังที่มีผลพร้อมการสืบทอดที่นำไปใช้. |
### getType() {#getType--}
```
public abstract byte getType()
```


ส่งคืนประเภทของการเติมพื้นหลัง. อ่าน/เขียน [BackgroundType](../../com.aspose.slides/backgroundtype).

**คืนค่า:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


ส่งคืนประเภทของการเติมพื้นหลัง. อ่าน/เขียน [BackgroundType](../../com.aspose.slides/backgroundtype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


ส่งคืน FillFormat สำหรับการเติม BackgroundType.OwnBackground. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```


ส่งคืน EffectFormat สำหรับการเติม BackgroundType.OwnBackground. อ่านอย่างเดียว [IEffectFormat](../../com.aspose.slides/ieffectformat).

**คืนค่า:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```


ส่งคืน ColorFormat สำหรับการเติม BackgroundType.Themed. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```


ส่งคืนดัชนีของการเติม BackgroundType.Themed ในคอลเลกชันธีมพื้นหลัง. 0 หมายถึงไม่มีการเติม. 1..999 - ดัชนี. อ่าน/เขียน int.

**คืนค่า:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```


ส่งคืนดัชนีของการเติม BackgroundType.Themed ในคอลเลกชันธีมพื้นหลัง. 0 หมายถึงไม่มีการเติม. 1..999 - ดัชนี. อ่าน/เขียน int.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```


รับข้อมูลพื้นหลังที่มีผลพร้อมการสืบทอดที่นำไปใช้.

**คืนค่า:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).