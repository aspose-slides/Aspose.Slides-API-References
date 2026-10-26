---
title: AddClone()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เพิ่มสำเนาของสไลด์มาสเตอร์ที่ระบุไปยังส่วนท้ายของคอลเลกชัน สไลด์เลเอาต์ที่เชื่อมโยงจะถูกคัดลอกด้วยเช่นกัน.
type: docs
weight: 53
url: /th/aspose.slides/imasterslidecollection/addclone/
---
## IMasterSlideCollection::AddClone(System::SharedPtr\<IMasterSlide\>) method

Adds a copy of a specified master slide to the end of the collection. Linked layout slides will be copied too.

```cpp
virtual System::SharedPtr<IMasterSlide> Aspose::Slides::IMasterSlideCollection::AddClone(System::SharedPtr<IMasterSlide> sourceMaster)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) เพื่อทำสำเนา. |

### ค่าที่คืนกลับ

สไลด์ที่เพิ่ม.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMasterSlide](../../imasterslide/)
* คลาส [IMasterSlideCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)