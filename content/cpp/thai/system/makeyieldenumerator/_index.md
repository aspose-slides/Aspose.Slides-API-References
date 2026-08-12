---
title: MakeYieldEnumerator()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้าง IEnumerator จากฟังก์ชัน yield.
type: docs
weight: 2432
url: /th/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator(const Details::YieldFunction\<T\>\&) function


สร้าง IEnumerator จากฟังก์ชัน yield

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดขององค์ประกอบในลำดับ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | ฟังก์ชัน yield ที่จะดำเนินการ |

### ค่าที่ส่งคืน

Shared pointer to the IEnumerator

## ดูเพิ่มเติม

* ชนิดนิยาม [SharedPtr](../sharedptr/)
* คลาส [IEnumerator](../../system.collections.generic/ienumerator/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)