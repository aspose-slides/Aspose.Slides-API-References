---
title: Reorder()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่กำหนด
type: docs
weight: 105
url: /th/aspose.slides/islidecollection/reorder/
---
## ISlideCollection::Reorder(int32_t, System::SharedPtr\<ISlide\>) เมธอด

ย้ายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ.

```cpp
virtual void Aspose::Slides::ISlideCollection::Reorder(int32_t index, System::SharedPtr<ISlide> slide)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีเป้าหมาย |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) เพื่อย้าย |

## ISlideCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<ISlide\>\>\&) เมธอด

ย้ายสไลด์หลายสไลด์จากคอลเลกชันไปยังตำแหน่งที่ระบุ. [Slides](../../) จะถูกวางเริ่มตั้งแต่ดัชนีตามลำดับที่ปรากฏในรายการ.

```cpp
virtual void Aspose::Slides::ISlideCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<ISlide>> &slides)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | **int32_t** | ดัชนีเป้าหมาย |
| slides | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>\>\& | [Slides](../../) เพื่อย้าย |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [ISlide](../../islide/)
* คลาส [ISlideCollection](../)
* เนมสเปส [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)