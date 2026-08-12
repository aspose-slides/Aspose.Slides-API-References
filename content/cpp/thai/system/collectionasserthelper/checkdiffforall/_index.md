---
title: CheckDiffForAll()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ตรวจสอบว่าทุกองค์ประกอบของคอลเลกชันปฏิบัติตามพรีดิเช็ต
type: docs
weight: 14
url: /th/system/collectionasserthelper/checkdiffforall/
---
## CollectionAssertHelper::CheckDiffForAll(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) เมธอด

ตรวจสอบว่าองค์ประกอบทั้งหมดของคอลเลกชันปฏิบัติตามพรีดิเช็ต

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAll(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | พรีดิเช็ตสำหรับตรวจสอบ |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | ค่าที่ต้องตรวจสอบ |

### ค่าที่คืนกลับ

คืนค่า false หากการตรวจสอบล้มเหลวสำหรับองค์ประกอบใด ๆ คืนค่า true หากทั้งหมดผ่าน

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [ICollection](../../../system.collections.generic/icollection/)
* โครงสร้าง [CollectionAssertHelper](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)