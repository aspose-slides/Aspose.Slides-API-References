---
title: InsertClone()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน
type: docs
weight: 27
url: /th/aspose.slides/islidecollection/insertclone/
---
## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) เมธอด

แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide)=0
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีของสไลด์ใหม่ |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) เพื่อทำการโคลน |

### ผลลัพธ์

สไลด์ที่แทรกแล้ว

## หมายเหตุ

เมื่อทำการโคลนสไลด์ระหว่างงานนำเสนอที่ต่างกัน มาสเตอร์ของสไลด์อาจถูกโคลนด้วย. มีการใช้เรจิสทรีภายในเพื่อติดตามมาสเตอร์ที่โคลนโดยอัตโนมัติเพื่อป้องกันการสร้างโคลนหลายอันของมาสเตอร์สไลด์เดียวกัน. การโคลนมาสเตอร์สไลด์ด้วยตนเองจะไม่ถูกป้องกันหรือบันทึก. หากคุณต้องการควบคุมกระบวนการโคลนเพิ่มเติมให้ใช้ [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) หรือ [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) สำหรับการโคลนสไลด์และ [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) สำหรับการโคลนมาสเตอร์

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) เมธอด

แทรกสำเนาของสไลด์ที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีของสไลด์ใหม่ |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) เพื่อทำการโคลน |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | เลย์เอาต์สไลด์สำหรับสไลด์ใหม่ |

### ผลลัพธ์

สไลด์ที่แทรกแล้ว

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) เมธอด

แทรกสำเนาของสไลด์ต้นฉบับที่ระบุไปยังตำแหน่งที่กำหนดของคอลเลกชัน. เลย์เอาต์ที่เหมาะสมจะถูกเลือกโดยอัตโนมัติโดยอิงจากมาสเตอร์ที่ระบุ (เลย์เอาต์ที่เหมาะสมคือเลย์เอาต์ที่มี Type หรือ Name เดียวกันกับเลย์เอาต์ของสไลด์ต้นฉบับ). หากไม่มีเลย์เอาต์ที่เหมาะสม เลย์เอาต์ของสไลด์ต้นฉบับจะถูกโคลน (หาก allowCloneMissingLayout เป็น true) หรือจะเกิด PptxEditException (หาก allowCloneMissingLayout เป็น false)

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีของสไลด์ใหม่ |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) เพื่อทำการโคลน |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | มาสเตอร์สไลด์สำหรับสไลด์ใหม่ |
| allowCloneMissingLayout | **bool** | หากไม่มีเลย์เอาต์ที่เหมาะสมในมาสเตอร์ที่ระบุ then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false) |

### ผลลัพธ์

สไลด์ที่แทรกแล้ว

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [ISlideCollection](../)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)