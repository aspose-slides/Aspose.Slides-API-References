---
title: ToArray()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างและคืนค่าอาร์เรย์ที่ประกอบด้วยรูปร่างทั้งหมด.
type: docs
weight: 287
url: /th/aspose.slides/ishapecollection/toarray/
---
## IShapeCollection::ToArray() method

สร้างและคืนค่าอาร์เรย์ที่ประกอบด้วยรูปร่างทั้งหมด.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray()=0
```

### ค่าที่คืน

อาร์เรย์ของอ็อบเจกต์ [IShape](../../ishape/).

## IShapeCollection::ToArray(int32_t, int32_t) method

สร้างและคืนค่าอาร์เรย์ที่ประกอบด้วยรูปร่างทั้งหมดในช่วงที่ระบุ.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| startIndex | **int32_t** | ดัชนีของรูปร่างแรกที่ต้องการคืนค่า. |
| count | **int32_t** | จำนวนของรูปร่างที่ต้องการคืนค่า. |

### ค่าที่คืน

อาร์เรย์ของอ็อบเจกต์ [IShape](../../ishape/).

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IShape](../../ishape/)
* คลาส [IShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)