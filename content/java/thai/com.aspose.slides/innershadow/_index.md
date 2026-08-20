---
title: InnerShadow
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นตัวแทนของเอฟเฟกต์เงาภายใน
type: docs
url: /th/com.aspose.slides/innershadow/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IInnerShadow](../../com.aspose.slides/iinnershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class InnerShadow implements IInnerShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Represents a Inner Shadow effect.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | รัศมีการเบลอ. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | รัศมีการเบลอ. |
| [getDirection()](#getDirection--) | ทิศทางของเงา. |
| [setDirection(float value)](#setDirection-float-) | ทิศทางของเงา. |
| [getDistance()](#getDistance--) | ระยะของเงา. |
| [setDistance(double value)](#setDistance-double-) | ระยะของเงา. |
| [getShadowColor()](#getShadowColor--) | สีของเงา. |
| [getEffective()](#getEffective--) | รับข้อมูลเอฟเฟกต์เงาภายในที่มีผลตามการสืบทอดที่ใช้. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่า [InnerShadow](../../com.aspose.slides/innershadow) ที่ระบุเท่ากับ [InnerShadow](../../com.aspose.slides/innershadow) ปัจจุบันหรือไม่. |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทที่ระบุ. |
### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

รัศมีการเบลอ. อ่าน/เขียน double.

**Returns:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

รัศมีการเบลอ. อ่าน/เขียน double.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public final float getDirection()
```

ทิศทางของเงา. อ่าน/เขียน float.

**Returns:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

ทิศทางของเงา. อ่าน/เขียน float.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```

ระยะของเงา. อ่าน/เขียน double.

**Returns:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

ระยะของเงา. อ่าน/เขียน double.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

สีของเงา. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IInnerShadowEffectiveData getEffective()
```

รับข้อมูลเอฟเฟกต์เงาภายในที่มีผลตามการสืบทอดที่ใช้.

**Returns:**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata) - หนึ่ง [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่าอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**Returns:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

คืนค่า parent IPresentationComponent. อ่านอย่างเดียว [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Returns:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

กำหนดว่า [InnerShadow](../../com.aspose.slides/innershadow) ที่ระบุเท่ากับ [InnerShadow](../../com.aspose.slides/innershadow) ปัจจุบันหรือไม่.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | The [InnerShadow](../../com.aspose.slides/innershadow) to compare. |

**Returns:**
boolean - true หากวัตถุเท่ากัน; มิฉะนั้น false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทที่ระบุ.

**Returns:**
int - รหัสแฮชสำหรับอ็อบเจ็กต์ปัจจุบัน.