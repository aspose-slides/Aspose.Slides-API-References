---
title: TryGetLast()
second_title: Aspose.Slides สำหรับ API ของ C++
description: พยายามดึงอิลีเมนต์สุดท้ายของคอลเลกชัน.
type: docs
weight: 261
url: /th/system.collections.generic.details/trygetlast/
---
## System::Collections::Generic::Details::TryGetLast(IEnumerable\<T\>\&, bool\&) ฟังก์ชัน

พยายามดึงเอาอิลีเมนต์สุดท้ายของคอลเลกชัน

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetLast(IEnumerable<T> &enumerable, bool &found)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดของอิลีเมนต์ในคอลเลกชัน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | คอลเลกชันที่ต้องการดึงอิลีเมนต์ |
| found | **bool**\& | พารามิเตอร์ผลลัพธ์ คืนค่า true หากคอลเลกชันมีอิลีเมนต์ใด ๆ มิฉะนั้นจะคืนค่า false |

### ค่าที่คืนกลับ

คืนค่าอิลีเมนต์สุดท้ายของคอลเลกชัน หากคอลเลกชันว่างจะคืนค่ามาตรฐานของชนิดนั้น

## ดูเพิ่มเติม

* คลาส [IEnumerable](../../system.collections.generic/ienumerable/)
* เนมสเปซ [System::Collections::Generic::Details](../)
* ไลบรารี [Aspose.Slides](../../)