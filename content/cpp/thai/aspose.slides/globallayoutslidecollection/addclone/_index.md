---
title: AddClone()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เพิ่มสำเนาของสไลด์เลเอาต์ที่ระบุลงในงานนำเสนอ
type: docs
weight: 1
url: /th/aspose.slides/globallayoutslidecollection/addclone/
---
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) เมธอด

เพิ่มสำเนาของสไลด์เลเอาต์ที่ระบุลงในงานนำเสนอ

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) เพื่อทำการโคลน. |

### ค่าที่ส่งคืน

สไลด์ที่เพิ่ม

## หมายเหตุ

เมื่อทำการโคลนเลเอาต์ระหว่างงานนำเสนอที่แตกต่างกัน มาสเตอร์ของเลเอาต์ก็สามารถถูกโคลนได้ด้วยเพื่อรักษาการจัดรูปแบบของต้นฉบับ การลงทะเบียนภายในจะใช้เพื่อติดตามมาสเตอร์ที่ถูกโคลนโดยอัตโนมัติเพื่อป้องกันการสร้างโคลนหลายครั้งของสไลด์มาสเตอร์เดียวกัน การโคลนมาสเตอร์สไลด์ด้วยตนเองจะไม่ถูกป้องกันหรือบันทึก

## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) เมธอด

เพิ่มสำเนาของสไลด์เลเอาต์ที่ระบุลงในงานนำเสนอ

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) เพื่อทำการโคลน. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | สไลด์มาสเตอร์สำหรับเลเอาต์ใหม่. |

### ค่าที่ส่งคืน

สไลด์ที่เพิ่ม

## หมายเหตุ

1) เลเอาต์ใหม่จะเชื่อมโยงกับมาสเตอร์ที่กำหนดในงานนำเสนอปลายทาง ดังนั้นจึงเป็นการทำงานที่คล้ายกับคัดลอก/วางโดยมีตัวเลือก "Use Destination Theme" ใน PowerPoint. 2) สิ่งที่คล้ายกับเมธอดนี้คือเมธอด [IMasterLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../imasterlayoutslidecollection/addclone/) ที่เข้าถึงได้ผ่านคุณสมบัติ [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/).

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ILayoutSlide](../../ilayoutslide/)
* คลาส [GlobalLayoutSlideCollection](../)
* คลาส [IMasterSlide](../../imasterslide/)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)