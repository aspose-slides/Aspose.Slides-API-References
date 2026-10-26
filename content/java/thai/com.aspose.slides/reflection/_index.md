---
title: Reflection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงเอฟเฟ็กต์การสะท้อน.
type: docs
url: /th/com.aspose.slides/reflection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IReflection](../../com.aspose.slides/ireflection), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Reflection implements IReflection, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

แสดงถึงเอฟเฟ็กต์การสะท้อน.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | ระบุตำแหน่งเริ่มต้น (ตามขั้นตอนสีไล่ระดับอัลฟ่า) ของค่าอัลฟ่าเริ่มต้น (เปอร์เซ็นต์). |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | ระบุตำแหน่งเริ่มต้น (ตามขั้นตอนสีไล่ระดับอัลฟ่า) ของค่าอัลฟ่าเริ่มต้น (เปอร์เซ็นต์). |
| [getEndPosAlpha()](#getEndPosAlpha--) | ระบุตำแหน่งสุดท้าย (ตามขั้นตอนสีไล่ระดับอัลฟ่า) ของค่าอัลฟ่าสุดท้าย (เปอร์เซ็นต์). |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | ระบุตำแหน่งสุดท้าย (ตามขั้นตอนสีไล่ระดับอัลฟ่า) ของค่าอัลฟ่าสุดท้าย (เปอร์เซ็นต์). |
| [getFadeDirection()](#getFadeDirection--) | ระบุทิศทางการเลื่อนการสะท้อน. |
| [setFadeDirection(float value)](#setFadeDirection-float-) | ระบุทิศทางการเลื่อนการสะท้อน. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | ความทึบของการสะท้อนเริ่มต้น. |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | ความทึบของการสะท้อนเริ่มต้น. |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | ความทึบของการสะท้อนสุดท้าย. |
| [setEndReflectionOpacity(float value)](#setEndReflectionOpacity-float-) | ความทึบของการสะท้อนสุดท้าย. |
| [getBlurRadius()](#getBlurRadius--) | รัศมีการเบลอ. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | รัศมีการเบลอ. |
| [getDirection()](#getDirection--) | ทิศทางของการสะท้อน. |
| [setDirection(float value)](#setDirection-float-) | ทิศทางของการสะท้อน. |
| [getDistance()](#getDistance--) | ระยะห่างของการสะท้อน. |
| [setDistance(double value)](#setDistance-double-) | ระยะห่างของการสะท้อน. |
| [getRectangleAlign()](#getRectangleAlign--) | การจัดตำแหน่งสี่เหลี่ยม. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | การจัดตำแหน่งสี่เหลี่ยม. |
| [getSkewHorizontal()](#getSkewHorizontal--) | ระบุมุมเบี่ยงแนวนอน. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | ระบุมุมเบี่ยงแนวนอน. |
| [getSkewVertical()](#getSkewVertical--) | ระบุมุมเบี่ยงแนวตั้ง. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | ระบุมุมเบี่ยงแนวตั้ง. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | ระบุว่าการสะท้อนควรหมุนตามรูปร่างหรือไม่ หากรูปร่างถูกหมุน. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | ระบุว่าการสะท้อนควรหมุนตามรูปร่างหรือไม่ หากรูปร่างถูกหมุน. |
| [getScaleHorizontal()](#getScaleHorizontal--) | ระบุตัวค่าสเกลแนวนอน, การสเกลที่เป็นค่าติดลบทำให้พลิกภาพ. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | ระบุตัวค่าสเกลแนวนอน, การสเกลที่เป็นค่าติดลบทำให้พลิกภาพ. |
| [getScaleVertical()](#getScaleVertical--) | ระบุตัวค่าสเกลแนวตั้ง, การสเกลที่เป็นค่าติดลบทำให้พลิกภาพ. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | ระบุตัวค่าสเกลแนวตั้ง, การสเกลที่เป็นค่าติดลบทำให้พลิกภาพ. |
| [getEffective()](#getEffective--) | ดึงข้อมูลเอฟเฟ็กต์การสะท้อนที่มีผลโดยการสืบทอด. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่าระบุ [Reflection](../../com.aspose.slides/reflection) เท่ากับ [Reflection](../../com.aspose.slides/reflection) ปัจจุบันหรือไม่. |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับชนิดเฉพาะ. |
### getStartPosAlpha() {#getStartPosAlpha--}
```
public final float getStartPosAlpha()
```


ระบุตำแหน่งเริ่มต้น (ตามขั้นตอนสีไล่ระดับอัลฟ่า) ของค่าอัลฟ่าเริ่มต้น (เปอร์เซ็นต์). อ่าน/เขียน float.

**ผลลัพธ์:**
float
### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public final void setStartPosAlpha(float value)
```


ระบุตำแหน่งเริ่มต้น (ตามขั้นตอนสีไล่ระดับอัลฟ่า) ของค่าอัลฟ่าเริ่มต้น (เปอร์เซ็นต์). อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### getEndPosAlpha() {#getEndPosAlpha--}
```
public final float getEndPosAlpha()
```


ระบุตำแหน่งสุดท้าย (ตามขั้นตอนสีไล่ระดับอัลฟ่า) ของค่าอัลฟ่าสุดท้าย (เปอร์เซ็นต์). อ่าน/เขียน float.

**ผลลัพธ์:**
float
### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public final void setEndPosAlpha(float value)
```


ระบุตำแหน่งสุดท้าย (ตามขั้นตอนสีไล่ระดับอัลฟ่า) ของค่าอัลฟ่าสุดท้าย (เปอร์เซ็นต์). อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### getFadeDirection() {#getFadeDirection--}
```
public final float getFadeDirection()
```


ระบุทิศทางการเลื่อนการสะท้อน. (angle). อ่าน/เขียน float.

**ผลลัพธ์:**
float
### setFadeDirection(float value) {#setFadeDirection-float-}
```
public final void setFadeDirection(float value)
```


ระบุทิศทางการเลื่อนการสะท้อน. (angle). อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public final float getStartReflectionOpacity()
```


ความทึบของการสะท้อนเริ่มต้น. (percents). อ่าน/เขียน float.

**ผลลัพธ์:**
float
### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public final void setStartReflectionOpacity(float value)
```


ความทึบของการสะท้อนเริ่มต้น. (percents). อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public final float getEndReflectionOpacity()
```


ความทึบของการสะท้อนสุดท้าย. (percents). อ่าน/เขียน float.

**ผลลัพธ์:**
float
### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public final void setEndReflectionOpacity(float value)
```


ความทึบของการสะท้อนสุดท้าย. (percents). อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```


รัศมีการเบลอ. อ่าน/เขียน double.

**ผลลัพธ์:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```


รัศมีการเบลอ. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public final float getDirection()
```


ทิศทางของการสะท้อน. อ่าน/เขียน float.

**ผลลัพธ์:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```


ทิศทางของการสะท้อน. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```


ระยะห่างของการสะท้อน. อ่าน/เขียน double.

**ผลลัพธ์:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


ระยะห่างของการสะท้อน. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |
### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```


การจัดตำแหน่งสี่เหลี่ยม. อ่าน/เขียน [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**ผลลัพธ์:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```


การจัดตำแหน่งสี่เหลี่ยม. อ่าน/เขียน [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |
### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```


ระบุมุมเบี่ยงแนวนอน. อ่าน/เขียน double.

**ผลลัพธ์:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```


ระบุมุมเบี่ยงแนวนอน. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |
### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```


ระบุมุมเบี่ยงแนวตั้ง. อ่าน/เขียน double.

**ผลลัพธ์:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```


ระบุมุมเบี่ยงแนวตั้ง. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```


ระบุว่าการสะท้อนควรหมุนตามรูปร่างหรือไม่ หากรูปร่างถูกหมุน. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```


ระบุว่าการสะท้อนควรหมุนตามรูปร่างหรือไม่ หากรูปร่างถูกหมุน. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```


ระบุตัวค่าสเกลแนวนอน, การสเกลที่เป็นค่าติดลบทำให้พลิกภาพ. (percents) อ่าน/เขียน double.

**ผลลัพธ์:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```


ระบุตัวค่าสเกลแนวนอน, การสเกลที่เป็นค่าติดลบทำให้พลิกภาพ. (percents) อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |
### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```


ระบุตัวค่าสเกลแนวตั้ง, การสเกลที่เป็นค่าติดลบทำให้พลิกภาพ. (percents) อ่าน/เขียน double.

**ผลลัพธ์:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```


ระบุตัวค่าสเกลแนวตั้ง, การสเกลที่เป็นค่าติดลบทำให้พลิกภาพ. (percents) อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |
### getEffective() {#getEffective--}
```
public final IReflectionEffectiveData getEffective()
```


ดึงข้อมูลเอฟเฟ็กต์การสะท้อนที่มีผลโดยการสืบทอด.

**ผลลัพธ์:**
[IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata) - A [IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


ส่งคืนวัตถุ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**ผลลัพธ์:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


เวอร์ชัน. อ่านอย่างเดียว long.

**ผลลัพธ์:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


ส่งคืน IPresentationComponent พาเรนต์. อ่านอย่างเดียว [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**ผลลัพธ์:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


กำหนดว่าระบุ [Reflection](../../com.aspose.slides/reflection) เท่ากับ [Reflection](../../com.aspose.slides/reflection) ปัจจุบันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | [Reflection](../../com.aspose.slides/reflection) ที่จะเปรียบเทียบ. |

**ผลลัพธ์:**
boolean - true หากอ็อบเจกต์เท่ากัน; มิฉะนั้น false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับชนิดเฉพาะ.

**ผลลัพธ์:**
int - รหัสแฮชสำหรับอ็อบเจกต์ปัจจุบัน.