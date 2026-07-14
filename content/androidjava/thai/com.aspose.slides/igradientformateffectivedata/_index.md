---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: อ็อบเจ็กต์ Imutable ที่มีคุณสมบัติการเติมไล่ระดับสีที่มีประสิทธิภาพ
type: docs
url: /th/com.aspose.slides/igradientformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

อ็อบเจ็กต์ Imutable ที่มีคุณสมบัติการเติมไล่ระดับสีที่มีประสิทธิภาพ.

--------------------

อินเทอร์เฟซนี้ใช้เป็นส่วนหนึ่งของ [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) และ [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | คืนค่าโหมดการพลิกของไล่ระดับสี |
| [getGradientDirection()](#getGradientDirection--) | คืนค่าสไตล์ของไล่ระดับสี |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | คืนค่ามุมของไล่ระดับสี |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | กำหนดว่าไล่ระดับสีถูกสเกลหรือไม่ |
| [getGradientShape()](#getGradientShape--) | คืนค่ารูปร่างของไล่ระดับสี |
| [getGradientStops()](#getGradientStops--) | คืนค่าคอลเลกชันของจุดหยุดไล่ระดับสี |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

คืนค่าโหมดการพลิกของไล่ระดับสี. อ่านอย่างเดียว [TileFlip](../../com.aspose.slides/tileflip).

**คืนค่า:**  
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

คืนค่าสไตล์ของไล่ระดับสี. อ่านอย่างเดียว [GradientDirection](../../com.aspose.slides/gradientdirection).

**คืนค่า:**  
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

คืนค่ามุมของไล่ระดับสี. อ่านอย่างเดียว float.

**คืนค่า:**  
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```

กำหนดว่าไล่ระดับสีถูกสเกลหรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**  
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

คืนค่ารูปร่างของไล่ระดับสี. อ่านอย่างเดียว [GradientShape](../../com.aspose.slides/gradientshape).

**คืนค่า:**  
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```

คืนค่าคอลเลกชันของจุดหยุดไล่ระดับสี. อ่านอย่างเดียว [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata).

**คืนค่า:**  
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)