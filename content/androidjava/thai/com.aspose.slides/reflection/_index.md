---
title: Reflection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงเอฟเฟกต์การสะท้อน.
type: docs
url: /th/com.aspose.slides/reflection/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IReflection](../../com.aspose.slides/ireflection), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Reflection implements IReflection, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

แสดงถึงเอฟเฟกต์ภาพสะท้อน
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | กำหนดตำแหน่งเริ่มต้น (ตามระดับสีกรเดียนอัลฟา) ของค่าอัลฟาเริ่มต้น (เปอร์เซ็นต์) |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | กำหนดตำแหน่งเริ่มต้น (ตามระดับสีกรเดียนอัลฟา) ของค่าอัลฟาเริ่มต้น (เปอร์เซ็นต์) |
| [getEndPosAlpha()](#getEndPosAlpha--) | กำหนดตำแหน่งสิ้นสุด (ตามระดับสีกรเดียนอัลฟา) ของค่าอัลฟาสิ้นสุด (เปอร์เซ็นต์) |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | กำหนดตำแหน่งสิ้นสุด (ตามระดับสีกรเดียนอัลฟา) ของค่าอัลฟาสิ้นสุด (เปอร์เซ็นต์) |
| [getFadeDirection()](#getFadeDirection--) | กำหนดทิศทางการชดเชยภาพสะท้อน |
| [setFadeDirection(float value)](#setFadeDirection-float-) | กำหนดทิศทางการชดเชยภาพสะท้อน |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | ความทึบแสงเริ่มต้นของภาพสะท้อน |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | ความทึบแสงเริ่มต้นของภาพสะท้อน |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | ความทึบแสงสุดท้ายของภาพสะท้อน |
| [setEndReflectionOpacity(float value)](#setEndReflectionOpacity-float-) | ความทึบแสงสุดท้ายของภาพสะท้อน |
| [getBlurRadius()](#getBlurRadius--) | รัศมีบลอร์ |
| [setBlurRadius(double value)](#setBlurRadius-double-) | รัศมีบลอร์ |
| [getDirection()](#getDirection--) | ทิศทางของภาพสะท้อน |
| [setDirection(float value)](#setDirection-float-) | ทิศทางของภาพสะท้อน |
| [getDistance()](#getDistance--) | ระยะทางของภาพสะท้อน |
| [setDistance(double value)](#setDistance-double-) | ระยะทางของภาพสะท้อน |
| [getRectangleAlign()](#getRectangleAlign--) | การจัดตำแหน่งสี่เหลี่ยม |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | การจัดตำแหน่งสี่เหลี่ยม |
| [getSkewHorizontal()](#getSkewHorizontal--) | กำหนดมุมเอียงแนวนอน |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | กำหนดมุมเอียงแนวนอน |
| [getSkewVertical()](#getSkewVertical--) | กำหนดมุมเอียงแนวตั้ง |
| [setSkewVertical(double value)](#setSkewVertical-double-) | กำหนดมุมเอียงแนวตั้ง |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | กำหนดว่าภาพสะท้อนควรหมุนพร้อมรูปทรงเมื่อรูปทรงถูกหมุนหรือไม่ |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | กำหนดว่าภาพสะท้อนควรหมุนพร้อมรูปทรงเมื่อรูปทรงถูกหมุนหรือไม่ |
| [getScaleHorizontal()](#getScaleHorizontal--) | กำหนดอัตราส่วนการขยายแนวนอน, การขยายเชิงลบทำให้พลิกกลับ | 
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | กำหนดอัตราส่วนการขยายแนวนอน, การขยายเชิงลบทำให้พลิกกลับ |
| [getScaleVertical()](#getScaleVertical--) | กำหนดอัตราส่วนการขยายแนวตั้ง, การขยายเชิงลบทำให้พลิกกลับ |
| [setScaleVertical(double value)](#setScaleVertical-double-) | กำหนดอัตราส่วนการขยายแนวตั้ง, การขยายเชิงลบทำให้พลิกกลับ |
| [getEffective()](#getEffective--) | รับข้อมูลเอฟเฟกต์ภาพสะท้อนที่มีผลลัพธ์จากการสืบทอด |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่าค่า [Reflection](../../com.aspose.slides/reflection) ที่ระบุเทียบเท่ากับ [Reflection](../../com.aspose.slides/reflection) ปัจจุบันหรือไม่ |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะ |

### getStartPosAlpha() {#getStartPosAlpha--}
```
public final float getStartPosAlpha()
```

กำหนดตำแหน่งเริ่มต้น (ตามระดับสีกรเดียนอัลฟา) ของค่าอัลฟาเริ่มต้น (เปอร์เซ็นต์) อ่าน/เขียน float.

**คืนค่า:**
float

### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public final void setStartPosAlpha(float value)
```

กำหนดตำแหน่งเริ่มต้น (ตามระดับสีกรเดียนอัลฟา) ของค่าอัลฟาเริ่มต้น (เปอร์เซ็นต์) อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getEndPosAlpha() {#getEndPosAlpha--}
```
public final float getEndPosAlpha()
```

กำหนดตำแหน่งสิ้นสุด (ตามระดับสีกรเดียนอัลฟา) ของค่าอัลฟาสิ้นสุด (เปอร์เซ็นต์) อ่าน/เขียน float.

**คืนค่า:**
float

### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public final void setEndPosAlpha(float value)
```

กำหนดตำแหน่งสิ้นสุด (ตามระดับสีกรเดียนอัลฟา) ของค่าอัลฟาสิ้นสุด (เปอร์เซ็นต์) อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getFadeDirection() {#getFadeDirection--}
```
public final float getFadeDirection()
```

กำหนดทิศทางการชดเชยภาพสะท้อน (มุม) อ่าน/เขียน float.

**คืนค่า:**
float

### setFadeDirection(float value) {#setFadeDirection-float-}
```
public final void setFadeDirection(float value)
```

กำหนดทิศทางการชดเชยภาพสะท้อน (มุม) อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public final float getStartReflectionOpacity()
```

ความทึบแสงเริ่มต้นของภาพสะท้อน (เปอร์เซ็นต์) อ่าน/เขียน float.

**คืนค่า:**
float

### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public final void setStartReflectionOpacity(float value)
```

ความทึบแสงเริ่มต้นของภาพสะท้อน (เปอร์เซ็นต์) อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public final float getEndReflectionOpacity()
```

ความทึบแสงสุดท้ายของภาพสะท้อน (เปอร์เซ็นต์) อ่าน/เขียน float.

**คืนค่า:**
float

### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public final void setEndReflectionOpacity(float value)
```

ความทึบแสงสุดท้ายของภาพสะท้อน (เปอร์เซ็นต์) อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

รัศมีบลอร์ อ่าน/เขียน double.

**คืนค่า:**
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

รัศมีบลอร์ อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

ทิศทางของภาพสะท้อน อ่าน/เขียน float.

**คืนค่า:**
float

### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

ทิศทางของภาพสะท้อน อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

ระยะทางของภาพสะท้อน อ่าน/เขียน double.

**คืนค่า:**
double

### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

ระยะทางของภาพสะท้อน อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```

การจัดตำแหน่งสี่เหลี่ยม อ่าน/เขียน [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**คืนค่า:**
byte

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```

การจัดตำแหน่งสี่เหลี่ยม อ่าน/เขียน [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```

กำหนดมุมเอียงแนวนอน อ่าน/เขียน double.

**คืนค่า:**
double

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```

กำหนดมุมเอียงแนวนอน อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```

กำหนดมุมเอียงแนวตั้ง อ่าน/เขียน double.

**คืนค่า:**
double

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```

กำหนดมุมเอียงแนวตั้ง อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```

กำหนดว่าภาพสะท้อนควรหมุนพร้อมรูปทรงเมื่อรูปทรงถูกหมุนหรือไม่ อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```

กำหนดว่าภาพสะท้อนควรหมุนพร้อมรูปทรงเมื่อรูปทรงถูกหมุนหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```

กำหนดอัตราส่วนการขยายแนวนอน, การขยายเชิงลบทำให้พลิกกลับ (เปอร์เซ็นต์) อ่าน/เขียน double.

**คืนค่า:**
double

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```

กำหนดอัตราส่วนการขยายแนวนอน, การขยายเชิงลบทำให้พลิกกลับ (เปอร์เซ็นต์) อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```

กำหนดอัตราส่วนการขยายแนวตั้ง, การขยายเชิงลบทำให้พลิกกลับ (เปอร์เซ็นต์) อ่าน/เขียน double.

**คืนค่า:**
double

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```

กำหนดอัตราส่วนการขยายแนวตั้ง, การขยายเชิงลบทำให้พลิกกลับ (เปอร์เซ็นต์) อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final IReflectionEffectiveData getEffective()
```

รับข้อมูลเอฟเฟกต์ภาพสะท้อนที่มีผลลัพธ์จากการสืบทอด

**คืนค่า:**
[IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata) - A [IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่าอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

คืนค่า parent IPresentationComponent. อ่านอย่างเดียว [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**คืนค่า:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

กำหนดว่าค่า [Reflection](../../com.aspose.slides/reflection) ที่ระบุเทียบเท่ากับ [Reflection](../../com.aspose.slides/reflection) ปัจจุบันหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | The [Reflection](../../com.aspose.slides/reflection) to compare. |

**คืนค่า:**
boolean - true if objects are equal; otherwise, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะ

**คืนค่า:**
int - A hash code for the current object.