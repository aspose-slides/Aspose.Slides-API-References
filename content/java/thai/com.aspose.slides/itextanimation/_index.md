---
title: ITextAnimation
second_title: Aspose.Slides for Java API Reference
description: Represent text animation.
type: docs
url: /th/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

แสดงการเคลื่อนไหวของข้อความ.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | เพิ่มเอฟเฟกต์ใหม่ลงในส่วนท้ายของลำดับปัจจุบันจนถึงส่วนท้ายของการเคลื่อนไหวข้อความแบบกลุ่ม. |
| [getBuildType()](#getBuildType--) | รายการประเภทการสร้าง (เช่น |
| [setBuildType(int value)](#setBuildType-int-) | รายการประเภทการสร้าง (เช่น |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | เอฟเฟ็กต์รูปร่างที่เชื่อมโยงกับกลุ่มหรือไม่ (null) อ่าน/เขียน [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | เอฟเฟ็กต์รูปร่างที่เชื่อมโยงกับกลุ่มหรือไม่ (null) อ่าน/เขียน [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```

เพิ่มเอฟเฟกต์ใหม่ลงในส่วนท้ายของลำดับปัจจุบันจนถึงส่วนท้ายของการเคลื่อนไหวข้อความแบบกลุ่ม. ใช้ได้เฉพาะเมื่อจำนวนย่อหน้าข้อความเท่ากับหรือมากกว่าจำนวนเอฟเฟกต์ของกลุ่มนี้!

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| effectType | int | ประเภทของเอฟเฟกต์แอนิเมชัน [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | ประเภทย่อยของเอฟเฟกต์แอนิเมชัน [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | ประเภทการเรียกใช้งานของเอฟเฟกต์ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**ผลลัพธ์:**
[IEffect](../../com.aspose.slides/ieffect) - อ็อบเจ็กต์เอฟเฟกต์ใหม่ [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```

รายการประเภทการสร้าง (เช่น ย่อหน้า 1,2,3, ทั้งหมดพร้อมกัน) ของการเคลื่อนไหวข้อความ. อ่าน/เขียน \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**ผลลัพธ์:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```

รายการประเภทการสร้าง (เช่น ย่อหน้า 1,2,3, ทั้งหมดพร้อมกัน) ของการเคลื่อนไหวข้อความ. อ่าน/เขียน \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```

เอฟเฟ็กต์รูปร่างที่เชื่อมโยงกับกลุ่มหรือไม่ (null) อ่าน/เขียน [IEffect](../../com.aspose.slides/ieffect).

**ผลลัพธ์:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```

เอฟเฟ็กต์รูปร่างที่เชื่อมโยงกับกลุ่มหรือไม่ (null) อ่าน/เขียน [IEffect](../../com.aspose.slides/ieffect).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |