---
title: FillOverlay
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงเอฟเฟกต์ Fill Overlay.
type: docs
url: /th/com.aspose.slides/filloverlay/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

แสดงถึงเอฟเฟกต์ Fill Overlay. Fill overlay สามารถใช้ระบุการเติมเพิ่มเติมสำหรับวัตถุและผสมการเติมสองแบบเข้าด้วยกัน.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | รูปแบบการเติม. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | ดึงข้อมูลเอฟเฟกต์ Fill Overlay ที่มีประสิทธิผลโดยใช้การสืบทอดที่นำมาใช้. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่า [FillOverlay](../../com.aspose.slides/filloverlay) ที่ระบุเป็นเท่ากับ [FillOverlay](../../com.aspose.slides/filloverlay) ปัจจุบันหรือไม่. |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทหนึ่ง. |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

รูปแบบการเติม. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBlend() {#getBlend--}
```
public final int getBlend()
```

FillBlendMode. อ่าน/เขียน [FillBlendMode](../../com.aspose.slides/fillblendmode).

**คืนค่า:**
int
### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```

FillBlendMode. อ่าน/เขียน [FillBlendMode](../../com.aspose.slides/fillblendmode).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```

ดึงข้อมูลเอฟเฟกต์ Fill Overlay ที่มีประสิทธิผลโดยใช้การสืบทอดที่นำมาใช้.

**คืนค่า:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - เป็น [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. อ่านอย่างเดียว long.

**คืนค่า:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

กำหนดว่า [FillOverlay](../../com.aspose.slides/filloverlay) ที่ระบุเป็นเท่ากับ [FillOverlay](../../com.aspose.slides/filloverlay) ปัจจุบันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | วัตถุ [FillOverlay](../../com.aspose.slides/filloverlay) เพื่อเปรียบเทียบ. |

**คืนค่า:**
boolean - true หากวัตถุเท่ากัน; มิฉะนั้น false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทหนึ่ง.

**คืนค่า:**
int - โค้ดแฮชสำหรับอ็อบเจกต์ปัจจุบัน.