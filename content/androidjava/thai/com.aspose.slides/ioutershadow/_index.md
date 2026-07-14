---
title: IOuterShadow
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นตัวแทนของเอฟเฟกต์เงานอก.
type: docs
url: /th/com.aspose.slides/ioutershadow/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

เป็นตัวแทนของเอฟเฟกต์เงานอก.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | รัศมีเบลอ, หน่วยเป็นจุด. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | รัศมีเบลอ, หน่วยเป็นจุด. |
| [getDirection()](#getDirection--) | ทิศทางของเงา, หน่วยเป็นองศา. |
| [setDirection(float value)](#setDirection-float-) | ทิศทางของเงา, หน่วยเป็นองศา. |
| [getDistance()](#getDistance--) | ระยะเงาจากวัตถุ, หน่วยเป็นจุด. |
| [setDistance(double value)](#setDistance-double-) | ระยะเงาจากวัตถุ, หน่วยเป็นจุด. |
| [getShadowColor()](#getShadowColor--) | สีของเงา. |
| [getRectangleAlign()](#getRectangleAlign--) | การจัดตำแหน่งสี่เหลี่ยม. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | การจัดตำแหน่งสี่เหลี่ยม. |
| [getSkewHorizontal()](#getSkewHorizontal--) | มุมเอียงแนวนอน, หน่วยเป็นองศา. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | มุมเอียงแนวนอน, หน่วยเป็นองศา. |
| [getSkewVertical()](#getSkewVertical--) | มุมเอียงแนวตั้ง, หน่วยเป็นองศา. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | มุมเอียงแนวตั้ง, หน่วยเป็นองศา. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | บ่งชี้ว่าเงาจะหมุนพร้อมกับรูปร่างหรือไม่. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | บ่งชี้ว่าเงาจะหมุนพร้อมกับรูปร่างหรือไม่. |
| [getScaleHorizontal()](#getScaleHorizontal--) | ปัจจัยการสเกลแนวนอน, หน่วยเป็นเปอร์เซ็นต์ของขนาดเดิม. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | ปัจจัยการสเกลแนวนอน, หน่วยเป็นเปอร์เซ็นต์ของขนาดเดิม. |
| [getScaleVertical()](#getScaleVertical--) | ปัจจัยการสเกลแนวตั้ง, หน่วยเป็นเปอร์เซ็นต์ของขนาดเดิม. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | ปัจจัยการสเกลแนวตั้ง, หน่วยเป็นเปอร์เซ็นต์ของขนาดเดิม. |

### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

รัศมีเบลอ, หน่วยเป็นจุด. ค่าเริ่มต้น - 0 pt. อ่าน/เขียน double.

**คืนค่า:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

รัศมีเบลอ, หน่วยเป็นจุด. ค่าเริ่มต้น - 0 pt. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

ทิศทางของเงา, หน่วยเป็นองศา. ค่าเริ่มต้น - 0 � (จากซ้ายไปขวา). อ่าน/เขียน float.

**คืนค่า:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

ทิศทางของเงา, หน่วยเป็นองศา. ค่าเริ่มต้น - 0 � (จากซ้ายไปขวา). อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

ระยะเงาจากวัตถุ, หน่วยเป็นจุด. ค่าเริ่มต้น - 0 pt. อ่าน/เขียน double.

**คืนค่า:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

ระยะเงาจากวัตถุ, หน่วยเป็นจุด. ค่าเริ่มต้น - 0 pt. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

สีของเงา. ค่าเริ่มต้น - สีดำอัตโนมัติ (ขึ้นกับธีม). อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

การจัดตำแหน่งสี่เหลี่ยม. ค่าเริ่มต้น - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). อ่าน/เขียน [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**คืนค่า:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

การจัดตำแหน่งสี่เหลี่ยม. ค่าเริ่มต้น - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). อ่าน/เขียน [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

มุมเอียงแนวนอน, หน่วยเป็นองศา. ค่าเริ่มต้น - 0 �. อ่าน/เขียน double.

**คืนค่า:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

มุมเอียงแนวนอน, หน่วยเป็นองศา. ค่าเริ่มต้น - 0 �. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

มุมเอียงแนวตั้ง, หน่วยเป็นองศา. ค่าเริ่มต้น - 0 �. อ่าน/เขียน double.

**คืนค่า:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

มุมเอียงแนวตั้ง, หน่วยเป็นองศา. ค่าเริ่มต้น - 0 �. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

บ่งชี้ว่าเงาจะหมุนพร้อมกับรูปร่างหรือไม่. ค่าเริ่มต้น - true. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

บ่งชี้ว่าเงาจะหมุนพร้อมกับรูปร่างหรือไม่. ค่าเริ่มต้น - true. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

ปัจจัยการสเกลแนวนอน, หน่วยเป็นเปอร์เซ็นต์ของขนาดเดิม. การสเกลเชิงลบทำให้พลิก. ค่าเริ่มต้น - 100 %. อ่าน/เขียน double.

**คืนค่า:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

ปัจจัยการสเกลแนวนอน, หน่วยเป็นเปอร์เซ็นต์ของขนาดเดิม. การสเกลเชิงลบทำให้พลิก. ค่าเริ่มต้น - 100 %. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

ปัจจัยการสเกลแนวตั้ง, หน่วยเป็นเปอร์เซ็นต์ของขนาดเดิม. การสเกลเชิงลบทำให้พลิก. ค่าเริ่มต้น - 100 %. อ่าน/เขียน double.

**คืนค่า:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

ปัจจัยการสเกลแนวตั้ง, หน่วยเป็นเปอร์เซ็นต์ของขนาดเดิม. การสเกลเชิงลบทำให้พลิก. ค่าเริ่มต้น - 100 %. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |