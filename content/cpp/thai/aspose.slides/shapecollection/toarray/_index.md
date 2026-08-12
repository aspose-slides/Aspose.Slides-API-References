---
title: ToArray()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างและคืนค่าอาร์เรย์ที่มีรูปร่างทั้งหมด.
type: docs
weight: 326
url: /th/aspose.slides/shapecollection/toarray/
---
## ShapeCollection::ToArray() เมธอด


สร้างและคืนค่าอาร์เรย์ที่มีรูปร่างทั้งหมด.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray() override
```


### ค่ารีเทิร์น

อาร์เรย์ของวัตถุ [IShape](../../ishape/).

## ShapeCollection::ToArray(int32_t, int32_t) เมธอด


สร้างและคืนค่าอาร์เรย์ที่มีรูปร่างทั้งหมดในช่วงที่ระบุ.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray(int32_t startIndex, int32_t count) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| startIndex | **int32_t** | ดัชนีของรูปร่างแรกที่ต้องการคืนค่า. |
| count | **int32_t** | จำนวนของรูปร่างที่ต้องการคืนค่า. |

### ค่ารีเทิร์น

อาร์เรย์ของวัตถุ [IShape](../../ishape/).

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IShape](../../ishape/)
* คลาส [ShapeCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)