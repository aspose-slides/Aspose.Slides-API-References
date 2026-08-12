---
title: LastIndexOfAny()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ค้นหาตัวอักษรใด ๆ ที่ส่งเข้ามาทั่วทั้งสตริงโดยการค้นจากท้ายไปต้น เปรียบเทียบอักษรสุดท้ายของสตริงกับอักขระทั้งหมดใน anyOf แล้วเปรียบเทียบอักขระก่อนหน้าและต่อไปเรื่อย ๆ ส่งคืนดัชนีของการจับคู่แรกที่พบ.
type: docs
weight: 664
url: /th/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const method

ค้นหาตัวอักษรใด ๆ ที่ส่งเข้ามาผ่านทั้งสตริงโดยการค้นจากท้ายไปต้น ตรวจสอบอักษรสุดท้ายของสตริงเทียบกับตัวอักษรทั้งหมดใน anyOf แล้วตรวจสอบอักษรก่อนหน้าและต่อไปเรื่อย ๆ ส่งคืนตำแหน่งของการจับคู่แรกที่พบ.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) ของอักขระที่ต้องการค้นหา. ลำดับไม่สำคัญ. |

### Return Value

[Index](../../index/) ของอักขระที่ตรงกันสุดท้ายหรือ -1 หากไม่พบ.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const method

ค้นหาตัวอักษรใด ๆ ที่ส่งเข้ามาผ่านสับสตริงโดยการค้นจากท้ายไปต้น ตรวจสอบอักษรสุดท้ายของสตริงเทียบกับตัวอักษรทั้งหมดใน anyOf แล้วตรวจสอบอักษรก่อนหน้าและต่อไปเรื่อย ๆ ส่งคืนตำแหน่งของการจับคู่แรกที่พบ.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) ของอักขระที่ต้องการค้นหา. ลำดับไม่สำคัญ. |
| startindex | **int32_t** | [Index](../../index/) เพื่อเริ่มการค้นหาจาก. |

### Return Value

[Index](../../index/) ของอักขระที่ตรงกันสุดท้ายหรือ -1 หากไม่พบ.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const method

ค้นหาตัวอักษรใด ๆ ที่ส่งเข้ามาผ่านสับสติ้งโดยการค้นจากท้ายไปต้น ตรวจสอบอักษรสุดท้ายของสตริงเทียบกับตัวอักษรทั้งหมดใน anyOf แล้วตรวจสอบอักษรก่อนหน้าและต่อไปเรื่อย ๆ ส่งคืนตำแหน่งของการจับคู่แรกที่พบ.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### Arguments

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) ของอักขระที่ต้องการค้นหา. ลำดับไม่สำคัญ. |
| startindex | **int32_t** | [Index](../../index/) เพื่อเริ่มการค้นหาจาก. |
| count | **int32_t** | จำนวนอักขระที่จะค้นหา. |

### Return Value

[Index](../../index/) ของอักขระที่ตรงกันสุดท้ายหรือ -1 หากไม่พบ.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* คลาส [String](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)