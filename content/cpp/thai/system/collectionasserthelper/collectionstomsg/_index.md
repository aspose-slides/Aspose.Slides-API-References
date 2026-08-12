---
title: CollectionsToMsg()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ทำการซีเรียลไลซ์คอลเลกชันสองชุดเพื่อการแสดงผลข้อความ
type: docs
weight: 53
url: /th/system/collectionasserthelper/collectionstomsg/
---
## CollectionAssertHelper::CollectionsToMsg(const System::String\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) เมธอด

ทำการซีเรียลไลซ์คอลเลกชันสองชุดสำหรับการแสดงผลข้อความ.

```cpp
template<typename T1,typename T2> static System::String System::CollectionAssertHelper::CollectionsToMsg(const System::String &extra_msg, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทขององค์ประกอบคอลเลกชันที่คาดหวัง. |
| T2 | ประเภทขององค์ประกอบคอลเลกชันที่เป็นจริง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| extra_msg | const [System::String](../../string/)\& | สตริงที่กำหนดเองซึ่งจะถูกแทรกก่อนค่าที่คาดหวังในข้อความผลลัพธ์ |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | คอลเลกชันที่คาดหวัง. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | คอลเลกชันจริง. |

### ค่าที่ส่งคืน

ข้อความที่เป็นมิตรต่อผู้ใช้เกี่ยวกับเนื้อหาของคอลเลกชัน

## ดูเพิ่มเติม

* ประเภทนิยาม [SharedPtr](../../sharedptr/)
* คลาส [String](../../string/)
* คลาส [IEnumerable](../../../system.collections.generic/ienumerable/)
* โครงสร้าง [CollectionAssertHelper](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)