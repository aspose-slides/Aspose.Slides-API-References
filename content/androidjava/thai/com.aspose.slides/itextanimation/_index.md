---
title: ITextAnimation
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงการเคลื่อนไหวของข้อความ.
type: docs
url: /th/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

แสดงการเคลื่อนไหวของข้อความ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | เพิ่มเอฟเฟกต์ใหม่ที่ส่วนท้ายของลำดับปัจจุบันจนถึงส่วนท้ายของการเคลื่อนไหวข้อความกลุ่ม. |
| [getBuildType()](#getBuildType--) | รายการประเภทการสร้าง (สำหรับตัวอย่าง |
| [setBuildType(int value)](#setBuildType-int-) | รายการประเภทการสร้าง (สำหรับตัวอย่าง |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | เอฟเฟกต์รูปร่างที่เชื่อมโยงกับกลุ่มหรือไม่ (null) อ่าน/เขียน [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | เอฟเฟกต์รูปร่างที่เชื่อมโยงกับกลุ่มหรือไม่ (null) อ่าน/เขียน [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```

เพิ่มเอฟเฟกต์ใหม่ที่ส่วนท้ายของลำดับปัจจุบันจนถึงส่วนท้ายของการเคลื่อนไหวข้อความกลุ่ม. ใช้ได้เฉพาะเมื่อจำนวนย่อหน้าข้อความเท่ากับหรือมากกว่าจำนวนเอฟเฟกต์ของกลุ่มนี้!

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| effectType | int | ประเภทของเอฟเฟกต์การเคลื่อนไหว [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | ประเภทย่อยของเอฟเฟกต์การเคลื่อนไหว [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | ประเภทการกระตุ้นของเอฟเฟกต์ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**คืนค่า:**
[IEffect](../../com.aspose.slides/ieffect) - อ็อบเจ็กต์เอฟเฟกต์ใหม่ [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```

รายการประเภทการสร้าง (สำหรับตัวอย่าง Paragraph 1,2,3, All at Once) ของการเคลื่อนไหวข้อความ. อ่าน/เขียน \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**คืนค่า:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```

รายการประเภทการสร้าง (สำหรับตัวอย่าง Paragraph 1,2,3, All at Once) ของการเคลื่อนไหวข้อความ. อ่าน/เขียน \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```

เอฟเฟกต์รูปร่างที่เชื่อมโยงกับกลุ่มหรือไม่ (null) อ่าน/เขียน [IEffect](../../com.aspose.slides/ieffect).

**คืนค่า:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```

เอฟเฟกต์รูปร่างที่เชื่อมโยงกับกลุ่มหรือไม่ (null) อ่าน/เขียน [IEffect](../../com.aspose.slides/ieffect).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |