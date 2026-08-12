---
title: ToArray()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างและคืนค่าอาเรย์ที่มีสไลด์ทั้งหมดอยู่ในนั้น.
type: docs
weight: 92
url: /th/aspose.slides/islidecollection/toarray/
---
## ISlideCollection::ToArray() เมธอด

สร้างและคืนค่าอาเรย์ที่มีสไลด์ทั้งหมดในนั้น.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray()=0
```

### ค่าที่ส่งคืน

อาเรย์ของ [ISlide](../../islide/)

## ISlideCollection::ToArray(int32_t, int32_t) เมธอด

สร้างและคืนค่าอาเรย์ที่มีสไลด์จากช่วงที่ระบุในนั้น.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| startIndex | **int32_t** | ดัชนีของสไลด์แรกที่ต้องการเพิ่ม |
| count | **int32_t** | จำนวนสไลด์ที่ต้องการเพิ่ม |

### ค่าที่ส่งคืน

อาเรย์ของ [ISlide](../../islide/)

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [ISlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)