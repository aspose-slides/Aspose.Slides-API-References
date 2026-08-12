---
title: AddClone()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เพิ่มสำเนาของสไลด์เลเอาต์ที่ระบุไปยังส่วนท้ายของคอลเลกชัน.
type: docs
weight: 1
url: /th/aspose.slides/masterlayoutslidecollection/addclone/
---
## MasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) เมธอด


เพิ่มสำเนาของสไลด์เลเอาต์ที่ระบุไปยังส่วนท้ายของคอลเลกชัน.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) เพื่อทำสำเนา. |

### คืนค่า

สไลด์ที่เพิ่ม.
## หมายเหตุ



1) เลเอาต์ใหม่จะถูกเชื่อมโยงกับสไลด์มาสเตอร์พาเรนท์สำหรับคอลเลกชันสไลด์เลเอาต์นี้ ดังนั้นนี่คือการทำงานที่คล้ายกับคัดลอก/วางพร้อมตัวเลือก "Use Destination Theme" ใน PowerPoint. 2) การทำงานที่คล้ายกับเมธอดนี้คือเมธอด [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) ที่เข้าถึงได้ผ่านคุณสมบัติ [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/). 
## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [ILayoutSlide](../../ilayoutslide/)
* คลาส [MasterLayoutSlideCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)