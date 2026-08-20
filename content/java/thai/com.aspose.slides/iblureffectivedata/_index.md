---
title: IBlurEffectiveData
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: อ็อบเจกต์แบบอ่านอย่างเดียวที่เป็นตัวแทนของเอฟเฟกต์ Blur ที่นำไปใช้กับรูปทรงทั้งหมดรวมถึงการเติมสีของมัน
type: docs
url: /th/com.aspose.slides/iblureffectivedata/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

ออบเจกต์แบบอ่านอย่างเดียวซึ่งเป็นตัวแทนของเอฟเฟกต์ Blur ที่นำไปใช้กับรูปทรงทั้งหมด รวมถึงการเติมสีของมัน ทั้งช่องสีทั้งหมดรวมถึงอัลฟาก็ได้รับผลกระทบเช่นกัน.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getRadius()](#getRadius--) | คืนค่า หรือ ตั้งค่ารัศมีการเบลอ. |
| [getGrow()](#getGrow--) | กำหนดว่าขอบเขตของออบเจกต์ควรขยายขึ้นเป็นผลมาจากการเบลอหรือไม่. |

### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

คืนค่า หรือ ตั้งค่ารัศมีการเบลอ. อ่านอย่างเดียว double.

**คืนค่า:**
double

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

กำหนดว่าขอบเขตของออบเจกต์ควรขยายขึ้นเป็นผลมาจากการเบลอหรือไม่. True ระบุว่าขอบเขตถูกขยายในขณะที่ false ระบุว่าไม่มีการขยาย. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean