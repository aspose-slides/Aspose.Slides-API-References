---
title: Background
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงพื้นหลังของสไลด์.
type: docs
url: /th/com.aspose.slides/background/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

แสดงถึงพื้นหลังของสไลด์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getType()](#getType--) | คืนค่าชนิดของการเติมพื้นหลัง. |
| [setType(byte value)](#setType-byte-) | คืนค่าชนิดของการเติมพื้นหลัง. |
| [getFillFormat()](#getFillFormat--) | คืนค่า FillFormat สำหรับการเติม BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | คืนค่า EffectFormat สำหรับการเติม BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | คืนค่า ColorFormat สำหรับการเติม BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | คืนค่าดัชนีของการเติม BackgroundType.Themed ในคอลเลกชันธีมพื้นหลัง. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | คืนค่าดัชนีของการเติม BackgroundType.Themed ในคอลเลกชันธีมพื้นหลัง. |
| [getEffective()](#getEffective--) | ดึงข้อมูลพื้นหลังที่มีผลการสืบทอด. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | คืนค่าสไลด์พาเรนต์ของ shape. |
| [getPresentation()](#getPresentation--) | คืนค่าการนำเสนอพาเรนต์ของสไลด์. |
### getType() {#getType--}
```
public final byte getType()
```


คืนค่าชนิดของการเติมพื้นหลัง. อ่าน/เขียน [BackgroundType](../../com.aspose.slides/backgroundtype).

**คืนค่า:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```


คืนค่าชนิดของการเติมพื้นหลัง. อ่าน/เขียน [BackgroundType](../../com.aspose.slides/backgroundtype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


คืนค่า FillFormat สำหรับการเติม BackgroundType.OwnBackground. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```


คืนค่า EffectFormat สำหรับการเติม BackgroundType.OwnBackground. อ่านอย่างเดียว [IEffectFormat](../../com.aspose.slides/ieffectformat).

**คืนค่า:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```


คืนค่า ColorFormat สำหรับการเติม BackgroundType.Themed. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```


คืนค่าดัชนีของการเติม BackgroundType.Themed ในคอลเลกชันธีมพื้นหลัง. 0 หมายถึงไม่มีการเติม. 1..999 - ดัชนี. อ่าน/เขียน int.

**คืนค่า:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```


คืนค่าดัชนีของการเติม BackgroundType.Themed ในคอลเลกชันธีมพื้นหลัง. 0 หมายถึงไม่มีการเติม. 1..999 - ดัชนี. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```


ดึงข้อมูลพื้นหลังที่มีผลการสืบทอด.

--------------------

> ```
> This example demonstrates getting effective background properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IBackgroundEffectiveData effectiveBackground = pres.getSlides().get_Item(0).getBackground().getEffective();
>  	System.out.println("Background fill type: " + effectiveBackground.getFillFormat().getFillType());
>  	System.out.println("Any effects applied: " + !effectiveBackground.getEffectFormat().isNoEffects());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


คืนค่าอ็อบเจกต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```


คืนค่าสไลด์พาเรนต์ของ shape. อ่านอย่างเดียว [IBaseSlide](../../com.aspose.slides/ibaseslide).

**คืนค่า:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```


คืนค่าการนำเสนอพาเรนต์ของสไลด์. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**
[Presentation](../../com.aspose.slides/presentation)