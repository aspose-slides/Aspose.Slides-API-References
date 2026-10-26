---
title: IAlphaBiLevel
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงเอฟเฟ็กต์ Alpha Bi-Level.
type: docs
url: /th/com.aspose.slides/ialphabilevel/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

เป็นผลกระทบ Alpha Bi-Level. ค่าของ Alpha (Opacity) ที่น้อยกว่าค่าขีดจำกัดจะถูกเปลี่ยนเป็น 0 (โปร่งใสเต็มที่) และค่าของ alpha ที่มากกว่าหรือเท่ากับค่าขีดจำกัดจะถูกเปลี่ยนเป็น 100% (ทึบเต็มที่).

--------------------

ใช้ ImageTransformOperationFactory เพื่อสร้างอินสแตนซ์ใน COM.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getThreshold()](#getThreshold--) | คืนค่าขีดจำกัดของเอฟเฟ็กต์. |
| [setThreshold(float value)](#setThreshold-float-) | คืนค่าขีดจำกัดของเอฟเฟ็กต์. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


คืนค่าขีดจำกัดของเอฟเฟ็กต์. อ่าน/เขียน float.

**คืนค่า:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```


คืนค่าขีดจำกัดของเอฟเฟ็กต์. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |