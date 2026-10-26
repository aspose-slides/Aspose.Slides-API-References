---
title: CheckDiffForAny()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตรวจสอบว่ามีองค์ประกอบใดในคอลเลกชันที่ตรงตามเงื่อนไข.
type: docs
weight: 27
url: /th/system/collectionasserthelper/checkdiffforany/
---
## CollectionAssertHelper::CheckDiffForAny(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) เมธอด

ตรวจสอบว่าองค์ประกอบใด ๆ ของคอลเลกชันตรงตามเงื่อนไขที่กำหนด

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAny(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | เงื่อนไขที่ต้องตรวจสอบ. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | ค่าที่ต้องตรวจสอบ. |

### ค่าที่ส่งคืน

True ถ้าการตรวจสอบสำเร็จสำหรับองค์ประกอบใด ๆ, false หากทั้งหมดผ่าน.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [ICollection](../../../system.collections.generic/icollection/)
* Struct [CollectionAssertHelper](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)