---
title: Equals()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดว่าตัวอย่างสองอ็อบเจกต์ของ IBaseSlide นั้นเท่ากันหรือไม่ ค่าที่ส่งกลับจะคำนวณจากโครงสร้างของสไลด์และเนื้อหาคงที่ สไลด์สองสไลด์จะเท่ากันหากรูปทรงทั้งหมด สไตล์ ข้อความ แอนิเมชันและการตั้งค่าอื่น ๆ เป็นต้น เท่ากัน การเปรียบเทียบจะไม่พิจารณาค่าตัวระบุที่เป็นเอกลักษณ์ เช่น SlideId และเนื้อหาแบบไดนามิก เช่น ค่าเวลาปัจจุบันในตัวยึดตำแหน่งวันที่
type: docs
weight: 183
url: /th/aspose.slides/ibaseslide/equals/
---
## IBaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) เมธอด


กำหนดว่าตัวอย่าง [IBaseSlide](../) สองตัวเท่ากันหรือไม่ ค่าที่ส่งกลับจะคำนวณจากโครงสร้างของสไลด์และเนื้อหาคงที่ สไลด์สองสไลด์เท่ากันหากรูปทรงทั้งหมด สไตล์ ข้อความ แอนิเมชันและการตั้งค่าอื่น ๆ เป็นต้น เท่ากัน การเปรียบเทียบจะไม่คำนึงถึงค่าตัวระบุที่เป็นเอกลักษณ์ เช่น SlideId และเนื้อหาไดนามิก เช่น ค่าที่เป็นวันที่ปัจจุบันใน Date [Placeholder](../../placeholder/).

```cpp
virtual bool Aspose::Slides::IBaseSlide::Equals(System::SharedPtr<IBaseSlide> slide)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../)\> | [IBaseSlide](../) ที่จะเปรียบเทียบกับ [IBaseSlide](../) ปัจจุบัน. |

### ค่าที่ส่งกลับ

**true** หาก [IBaseSlide](../) ที่ระบุเท่ากับ [IBaseSlide](../) ปัจจุบัน; มิฉะนั้น, **false**.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IBaseSlide](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)