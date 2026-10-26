---
title: IBlurEffectiveData
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: อ็อบเจ็กต์ที่ไม่สามารถเปลี่ยนแปลงได้ซึ่งเป็นตัวแทนของเอฟเฟกต์เบลอที่ถูกนำไปใช้กับรูปทรงทั้งหมดรวมถึงการเติมสีของมัน.
type: docs
url: /th/com.aspose.slides/iblureffectivedata/
---
**อินเทอร์เฟซที่ทำงานทั้งหมด:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

อ็อบเจ็กต์ที่ไม่สามารถเปลี่ยนแปลงได้ซึ่งเป็นตัวแทนของเอฟเฟกต์เบลอที่ถูกนำไปใช้กับรูปทรงทั้งหมดรวมถึงการเติมสีของมัน ช่องสีทั้งหมดรวมถึงอัลฟ่าก็ได้รับผลกระทบด้วย.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getRadius()](#getRadius--) | ส่งคืนหรือกำหนดรัศมีเบลอ. |
| [getGrow()](#getGrow--) | กำหนดว่าขอบเขตของอ็อบเจ็กต์ควรขยายเป็นผลมาจากการเบลอหรือไม่. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

ส่งคืนหรือกำหนดรัศมีเบลอ. อ่านอย่างเดียว double.

**ส่งคืน:**
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

กำหนดว่าขอบเขตของอ็อบเจ็กต์ควรขยายเป็นผลมาจากการเบลอหรือไม่. True ระบุว่าขอบเขตถูกขยายขณะที่ false ระบุว่าไม่ถูกขยาย. อ่านอย่างเดียว boolean.

**ส่งคืน:**
boolean