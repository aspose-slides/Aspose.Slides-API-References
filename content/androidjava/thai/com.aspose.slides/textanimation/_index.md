---
title: TextAnimation
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
description: แสดงการเคลื่อนไหวของข้อความ.
type: docs
url: /th/com.aspose.slides/textanimation/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

แสดงการเคลื่อนไหวของข้อความ.
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | เพิ่มเอฟเฟกต์ใหม่ที่ส่วนท้ายของลำดับปัจจุบันไปยังส่วนท้ายของกลุ่มการเคลื่อนไหวของข้อความ. |
| [getBuildType()](#getBuildType--) | รายการประเภทการสร้าง (เช่น |
| [setBuildType(int value)](#setBuildType-int-) | รายการประเภทการสร้าง (เช่น |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | เอฟเฟกต์รูปร่างที่เชื่อมโยงกับกลุ่มหรือไม่ (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | เอฟเฟกต์รูปร่างที่เชื่อมโยงกับกลุ่มหรือไม่ (null). |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```


### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```


เพิ่มเอฟเฟกต์ใหม่ที่ส่วนท้ายของลำดับปัจจุบันไปยังส่วนท้ายของกลุ่มการเคลื่อนไหวของข้อความ. ใช้ได้เฉพาะเมื่อจำนวนย่อหน้าข้อความเท่ากับหรือมากกว่าจำนวนเอฟเฟกต์ของกลุ่มนี้!

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| effectType | int | ประเภทของเอฟเฟกต์การเคลื่อนไหว [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | ชนิดย่อยของเอฟเฟกต์การเคลื่อนไหว [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | ประเภทการกระตุ้นของเอฟเฟกต์ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**ผลลัพธ์:**
[IEffect](../../com.aspose.slides/ieffect) - อ็อบเจ็กต์เอฟเฟกต์ใหม่ [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```


รายการประเภทการสร้าง (เช่น ย่อหน้า 1,2,3, ทั้งหมดพร้อมกัน) ของการเคลื่อนไหวของข้อความ. อ่าน/เขียน [BuildType](../../com.aspose.slides/buildtype).

**ผลลัพธ์:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```


รายการประเภทการสร้าง (เช่น ย่อหน้า 1,2,3, ทั้งหมดพร้อมกัน) ของการเคลื่อนไหวของข้อความ. อ่าน/เขียน [BuildType](../../com.aspose.slides/buildtype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```


เอฟเฟกต์รูปร่างที่เชื่อมโยงกับกลุ่มหรือไม่ (null). อ่าน/เขียน [IEffect](../../com.aspose.slides/ieffect).

**ผลลัพธ์:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```


เอฟเฟกต์รูปร่างที่เชื่อมโยงกับกลุ่มหรือไม่ (null). อ่าน/เขียน [IEffect](../../com.aspose.slides/ieffect).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |