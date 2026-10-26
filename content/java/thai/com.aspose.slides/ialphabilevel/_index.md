---
title: IAlphaBiLevel
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นตัวแทนของเอฟเฟกต์ Alpha Bi-Level.
type: docs
url: /th/com.aspose.slides/ialphabilevel/
---
**อินเทอร์เฟซที่นำมาใช้ทั้งหมด:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

แสดงเอฟเฟกต์ Alpha Bi-Level. ค่า Alpha (Opacity) ที่น้อยกว่าขีดจำกัดจะถูกเปลี่ยนเป็น 0 (โปร่งใสเต็ม) และค่าที่มากกว่าหรือเท่ากับขีดจำกัดจะถูกเปลี่ยนเป็น 100% (ทึบเต็ม)

--------------------

ใช้ ImageTransformOperationFactory เพื่อสร้างอินสแตนซ์ใน COM.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getThreshold()](#getThreshold--) | คืนค่าเกณฑ์ของเอฟเฟกต์ |
| [setThreshold(float value)](#setThreshold-float-) | คืนค่าเกณฑ์ของเอฟเฟกต์ |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


คืนค่าเกณฑ์ของเอฟเฟกต์. อ่าน/เขียน float.

**คืนค่า:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```


คืนค่าเกณฑ์ของเอฟเฟกต์. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |