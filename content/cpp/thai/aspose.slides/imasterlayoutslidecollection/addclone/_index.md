---
title: AddClone()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เพิ่มสำเนาของสไลด์เค้าโครงที่ระบุไปยังส่วนท้ายของคอลเลกชัน.
type: docs
weight: 1
url: /th/aspose.slides/imasterlayoutslidecollection/addclone/
---
## IMasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) เมธอด

เพิ่มสำเนาของสไลด์เค้าโครงที่กำหนดไว้ไปยังส่วนท้ายของคอลเลกชัน.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) เพื่อทำสำเนา. |

### ค่าที่คืน

สไลด์ที่เพิ่ม.

## หมายเหตุ

1) เค้าโครงใหม่จะถูกเชื่อมโยงกับสไลด์มาสเตอร์หลักสำหรับคอลเลกชันสไลด์เค้าโครงนี้ ดังนั้นนี่คือการทำงานที่คล้ายกับคัดลอก/วางโดยใช้ตัวเลือก \"Use Destination Theme\" ใน PowerPoint. 2) วิธีการที่คล้ายกับเมธอดนี้คือเมธอด [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) ที่เข้าถึงได้ผ่านคุณสมบัติ [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)