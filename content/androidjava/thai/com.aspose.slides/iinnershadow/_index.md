---
title: IInnerShadow
second_title: Aspose.Slides สำหรับ Android ผ่านเอกสารอ้างอิง Java API
description: แสดงเอฟเฟกต์เงาภายใน.
type: docs
url: /th/com.aspose.slides/iinnershadow/
---
**ทั้งหมดที่ใช้งานอินเทอร์เฟซ:**  
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject  
```
public interface IInnerShadow extends IImageTransformOperation, IAccessiblePVIObject<IInnerShadowEffectiveData>
```

แสดงเอฟเฟกต์เงาภายใน.  
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | รัศมีการเบลอ. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | รัศมีการเบลอ. |
| [getDirection()](#getDirection--) | ทิศทางของเงา. |
| [setDirection(float value)](#setDirection-float-) | ทิศทางของเงา. |
| [getDistance()](#getDistance--) | ระยะทางของเงา. |
| [setDistance(double value)](#setDistance-double-) | ระยะทางของเงา. |
| [getShadowColor()](#getShadowColor--) | สีของเงา. |

### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```


รัศมีการเบลอ. อ่าน/เขียน double.

**คืนค่า:**
double

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```


รัศมีการเบลอ. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


ทิศทางของเงา. อ่าน/เขียน float.

**คืนค่า:**
float

### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```


ทิศทางของเงา. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


ระยะทางของเงา. อ่าน/เขียน double.

**คืนค่า:**
double

### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```


ระยะทางของเงา. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```


สีของเงา. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)