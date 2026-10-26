---
title: IReflection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
description: แสดงถึงเอฟเฟกต์การสะท้อน.
type: docs
url: /th/com.aspose.slides/ireflection/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**  
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject  
```
public interface IReflection extends IImageTransformOperation, IAccessiblePVIObject<IReflectionEffectiveData>
```

แสดงถึงเอฟเฟกต์การสะท้อน  
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | ระบุตำแหน่งเริ่มต้น (ตามลาดสีอัลฟ่า) ของค่าอัลฟ่าเริ่มต้น (เปอร์เซ็นต์). |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | ระบุตำแหน่งเริ่มต้น (ตามลาดสีอัลฟ่า) ของค่าอัลฟ่าเริ่มต้น (เปอร์เซ็นต์). |
| [getEndPosAlpha()](#getEndPosAlpha--) | ระบุตำแหน่งสิ้นสุด (ตามลาดสีอัลฟ่า) ของค่าอัลฟ่าแบบสิ้นสุด (เปอร์เซ็นต์). |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | ระบุตำแหน่งสิ้นสุด (ตามลาดสีอัลฟ่า) ของค่าอัลฟ่าแบบสิ้นสุด (เปอร์เซ็นต์). |
| [getFadeDirection()](#getFadeDirection--) | ระบุทิศทางในการชดเชยการสะท้อน. |
| [setFadeDirection(float value)](#setFadeDirection-float-) | ระบุทิศทางในการชดเชยการสะท้อน. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | ความทึบแสงของการสะท้อนเริ่มต้น. |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | ความทึบแสงของการสะท้อนเริ่มต้น. |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | ความทึบแสงของการสะท้อนสุดท้าย. |
| [setEndReflectionOpacity(float value)](#setEndReflectionOpacity-float-) | ความทึบแสงของการสะท้อนสุดท้าย. |
| [getBlurRadius()](#getBlurRadius--) | รัศมีการเบลอ. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | รัศมีการเบลอ. |
| [getDirection()](#getDirection--) | ทิศทางของการสะท้อน. |
| [setDirection(float value)](#setDirection-float-) | ทิศทางของการสะท้อน. |
| [getDistance()](#getDistance--) | ระยะของการสะท้อน. |
| [setDistance(double value)](#setDistance-double-) | ระยะของการสะท้อน. |
| [getRectangleAlign()](#getRectangleAlign--) | การจัดตำแหน่งสี่เหลี่ยม. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | การจัดตำแหน่งสี่เหลี่ยม. |
| [getSkewHorizontal()](#getSkewHorizontal--) | ระบุมุมเอียงแนวนอน. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | ระบุมุมเอียงแนวนอน. |
| [getSkewVertical()](#getSkewVertical--) | ระบุมุมเอียงแนวตั้ง. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | ระบุมุมเอียงแนวตั้ง. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | ระบุว่าการสะท้อนควรหมุนพร้อมกับรูปร่างหรือไม่หากรูปร่างถูกหมุน. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | ระบุว่าการสะท้อนควรหมุนพร้อมกับรูปร่างหรือไม่หากรูปร่างถูกหมุน. |
| [getScaleHorizontal()](#getScaleHorizontal--) | ระบุปัจจัยการสเกลแนวนอน, การสเกลเป็นค่าลบทำให้เกิดการพลิก. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | ระบุปัจจัยการสเกลแนวนอน, การสเกลเป็นค่าลบทำให้เกิดการพลิก. |
| [getScaleVertical()](#getScaleVertical--) | ระบุปัจจัยการสเกลแนวตั้ง, การสเกลเป็นค่าลบทำให้เกิดการพลิก. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | ระบุปัจจัยการสเกลแนวตั้ง, การสเกลเป็นค่าลบทำให้เกิดการพลิก. |

### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```

ระบุตำแหน่งเริ่มต้น (ตามลาดสีอัลฟ่า) ของค่าอัลฟ่าเริ่มต้น (เปอร์เซ็นต์). อ่าน/เขียน float.

**คืนค่า:**  
float
### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public abstract void setStartPosAlpha(float value)
```

ระบุตำแหน่งเริ่มต้น (ตามลาดสีอัลฟ่า) ของค่าอัลฟ่าเริ่มต้น (เปอร์เซ็นต์). อ่าน/เขียน float.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```

ระบุตำแหน่งสิ้นสุด (ตามลาดสีอัลฟ่า) ของค่าอัลฟ่าแบบสิ้นสุด (เปอร์เซ็นต์). อ่าน/เขียน float.

**คืนค่า:**  
float
### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public abstract void setEndPosAlpha(float value)
```

ระบุตำแหน่งสิ้นสุด (ตามลาดสีอัลฟ่า) ของค่าอัลฟ่าแบบสิ้นสุด (เปอร์เซ็นต์). อ่าน/เขียน float.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```

ระบุทิศทางในการชดเชยการสะท้อน (มุม). อ่าน/เขียน float.

**คืนค่า:**  
float
### setFadeDirection(float value) {#setFadeDirection-float-}
```
public abstract void setFadeDirection(float value)
```

ระบุทิศทางในการชดเชยการสะท้อน (มุม). อ่าน/เขียน float.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```

ความทึบแสงของการสะท้อนเริ่มต้น (เปอร์เซ็นต์). อ่าน/เขียน float.

**คืนค่า:**  
float
### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public abstract void setStartReflectionOpacity(float value)
```

ความทึบแสงของการสะท้อนเริ่มต้น (เปอร์เซ็นต์). อ่าน/เขียน float.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```

ความทึบแสงของการสะท้อนสุดท้าย (เปอร์เซ็นต์). อ่าน/เขียน float.

**คืนค่า:**  
float
### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public abstract void setEndReflectionOpacity(float value)
```

ความทึบแสงของการสะท้อนสุดท้าย (เปอร์เซ็นต์). อ่าน/เขียน float.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

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

ทิศทางของการสะท้อน. อ่าน/เขียน float.

**คืนค่า:**  
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

ทิศทางของการสะท้อน. อ่าน/เขียน float.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

ระยะของการสะท้อน. อ่าน/เขียน double.

**คืนค่า:**  
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

ระยะของการสะท้อน. อ่าน/เขียน double.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

การจัดตำแหน่งสี่เหลี่ยม. อ่าน/เขียน [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**คืนค่า:**  
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

การจัดตำแหน่งสี่เหลี่ยม. อ่าน/เขียน [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

ระบุมุมเอียงแนวนอน. อ่าน/เขียน double.

**คืนค่า:**  
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

ระบุมุมเอียงแนวนอน. อ่าน/เขียน double.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

ระบุมุมเอียงแนวตั้ง. อ่าน/เขียน double.

**คืนค่า:**  
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

ระบุมุมเอียงแนวตั้ง. อ่าน/เขียน double.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

ระบุว่าการสะท้อนควรหมุนพร้อมกับรูปร่างหรือไม่หากรูปร่างถูกหมุน. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

ระบุว่าการสะท้อนควรหมุนพร้อมกับรูปร่างหรือไม่หากรูปร่างถูกหมุน. อ่าน/เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

ระบุปัจจัยการสเกลแนวนอน, การสเกลเป็นค่าลบทำให้เกิดการพลิก (เปอร์เซ็นต์). อ่าน/เขียน double.

**คืนค่า:**  
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

ระบุปัจจัยการสเกลแนวนอน, การสเกลเป็นค่าลบทำให้เกิดการพลิก (เปอร์เซ็นต์). อ่าน/เขียน double.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

ระบุปัจจัยการสเกลแนวตั้ง, การสเกลเป็นค่าลบทำให้เกิดการพลิก (เปอร์เซ็นต์). อ่าน/เขียน double.

**คืนค่า:**  
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

ระบุปัจจัยการสเกลแนวตั้ง, การสเกลเป็นค่าลบทำให้เกิดการพลิก (เปอร์เซ็นต์). อ่าน/เขียน double.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |