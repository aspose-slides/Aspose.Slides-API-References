---
title: DynamicCastArray()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ทำการแคสติ้งขององค์ประกอบของอาเรย์ที่ระบุเป็นประเภทที่ต่างกัน.
type: docs
weight: 2991
url: /th/system/dynamiccastarray/
---
## System::DynamicCastArray(const SharedPtr\<Array\<From\>\>\&) ฟังก์ชัน

ทำการแคสติ้งขององค์ประกอบของอาเรย์ที่ระบุเป็นประเภทที่แตกต่างกัน

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```

### Template parameters

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| To | ประเภทที่จะทำการแคสติ้งองค์ประกอบของอาเรย์ที่ระบุ |
| From | ประเภทขององค์ประกอบของอาเรย์ที่ต้องทำการแคส |

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| from | const [SharedPtr](../sharedptr/)\<[Array](../array/)\<From\>\>\& | ตัวชี้ชนิด Shared pointer ไปยังอาเรย์ที่มีองค์ประกอบที่จะทำการแคส |

### Return Value

ตัวชี้ไปยังอาเรย์ใหม่ที่มีองค์ประกอบประเภท **To** เทียบเท่ากับองค์ประกอบของ **from**

เลิกใช้
:   เพิ่มเพื่อความเข้ากันได้ย้อนหลัง ใช้ ExplicitCast แทน

## ดูเพิ่มเติม

* Typedef [SharedPtr](../sharedptr/)
* คลาส [Array](../array/)
* เนมสเปซ [System](../)
* Library [Aspose.Slides](../../)