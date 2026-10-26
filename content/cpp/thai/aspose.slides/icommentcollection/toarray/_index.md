---
title: ToArray()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างและส่งกลับอาร์เรย์ที่มีคอมเมนต์ทั้งหมด
type: docs
weight: 66
url: /th/aspose.slides/icommentcollection/toarray/
---
## ICommentCollection::ToArray() เมธอด

สร้างและส่งกลับอาร์เรย์ที่มีคอมเมนต์ทั้งหมด

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray()=0
```

### ค่าที่ส่งกลับ

อาร์เรย์ของ [IComment](../../icomment/).

## ICommentCollection::ToArray(int32_t, int32_t) เมธอด

สร้างและส่งกลับอาร์เรย์ที่มีคอมเมนต์ทั้งหมดจากช่วงที่ระบุ

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| startIndex | **int32_t** | ดัชนีของคอมเมนต์แรกที่ต้องส่งกลับ |
| count | **int32_t** | จำนวนคอมเมนต์ที่ต้องส่งกลับ |

### ค่าที่ส่งกลับ

อาร์เรย์ของ [IComment](../../icomment/).

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IComment](../../icomment/)
* คลาส [ICommentCollection](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)