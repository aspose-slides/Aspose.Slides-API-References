---
title: ToArray()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างและคืนค่าอาร์เรย์ที่มีคอมเมนต์ทั้งหมด.
type: docs
weight: 105
url: /th/aspose.slides/commentcollection/toarray/
---
## CommentCollection::ToArray() เมธอด

สร้างและคืนค่าอาร์เรย์ที่มีคอมเมนต์ทั้งหมด.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray() override
```

### ค่าที่คืน

อาร์เรย์ของ [Comment](../../comment/).

## CommentCollection::ToArray(int32_t, int32_t) เมธอด

สร้างและคืนค่าอาร์เรย์ที่มีคอมเมนต์ทั้งหมดจากช่วงที่ระบุ.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray(int32_t startIndex, int32_t count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| startIndex | **int32_t** | ดัชนีของคอมเมนต์แรกที่ต้องการคืน. |
| count | **int32_t** | จำนวนของคอมเมนต์ที่ต้องการคืน. |

### ค่าที่คืน

อาร์เรย์ของ [Comment](../../comment/).

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IComment](../../icomment/)
* คลาส [CommentCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)