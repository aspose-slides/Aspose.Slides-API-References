---
title: TryGetFirst()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: พยายามดึงองค์ประกอบแรกของคอลเลกชัน
type: docs
weight: 248
url: /th/system.collections.generic.details/trygetfirst/
---
## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, bool\&) ฟังก์ชัน

พยายามดึงองค์ประกอบแรกของคอลเลกชัน.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, bool &found)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในคอลเลกชัน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | คอลเลกชันที่ต้องการดึงองค์ประกอบ |
| found | **bool**\& | พารามิเตอร์ผลลัพธ์ คืนค่า true เมื่อคอลเลกชันมีองค์ประกอบใด ๆ มิฉะนั้นจะคืนค่า false |

### ค่าที่คืนกลับ

คืนค่าองค์ประกอบแรกของคอลเลกชัน หากคอลเลกชันว่างจะคืนค่าพื้นฐานของประเภทนั้น

## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, const Func\<T, bool\>\&, bool\&) ฟังก์ชัน

พยายามดึงองค์ประกอบแรกของคอลเลกชันที่ตรงกับฟังก์ชันเงื่อนไข

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, const Func<T, bool> &predicate, bool &found)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในคอลเลกชัน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | คอลเลกชันที่ต้องการดึงองค์ประกอบ |
| predicate | const [Func](../../system/func/)\<T, **bool**\>\& | ฟังก์ชันเงื่อนไข |
| found | **bool**\& | พารามิเตอร์ผลลัพธ์ คืนค่า true เมื่อคอลเลกชันมีองค์ประกอบใด ๆ มิฉะนั้นจะคืนค่า false |

### ค่าที่คืนกลับ

คืนค่าองค์ประกอบแรกของคอลเลกชัน หากไม่พบองค์ประกอบใดที่ตรงกับฟังก์ชันเงื่อนไขที่ระบุ จะคืนค่าพื้นฐานของประเภทนั้น

## ดูเพิ่มเติม

* คลาส [IEnumerable](../../system.collections.generic/ienumerable/)
* คลาส [Func](../../system/func/)
* เนมสเปซ [System::Collections::Generic::Details](../)
* ไลบรารี [Aspose.Slides](../../)