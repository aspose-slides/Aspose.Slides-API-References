---
title: MakeYieldEnumerable()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้าง IEnumerable จากฟังก์ชัน yield.
type: docs
weight: 2419
url: /th/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable(const Details::YieldFunction\<T\>\) ฟังก์ชัน

สร้าง IEnumerable จากฟังก์ชัน yield.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในลำดับ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | ฟังก์ชัน yield ที่จะดำเนินการ |

### ค่าที่คืน

ตัวชี้ร่วมไปยัง IEnumerable

## ดูเพิ่มเติม

* Typedef [SharedPtr](../sharedptr/)
* คลาส [IEnumerable](../../system.collections.generic/ienumerable/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)