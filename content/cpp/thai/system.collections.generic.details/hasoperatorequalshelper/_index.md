---
title: HasOperatorEqualsHelper()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ฟังก์ชันช่วยเหลือเพื่อกำหนดว่าคลาสเฉพาะมีตัวดำเนินการ == หรือไม่.
type: docs
weight: 235
url: /th/system.collections.generic.details/hasoperatorequalshelper/
---
## System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *) ฟังก์ชัน

ฟังก์ชันช่วยเหลือเพื่อกำหนดว่าคลาสเฉพาะมีตัวดำเนินการ == หรือไม่.

```cpp
template<class T,typename Dummy> std::true_type System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | ประเภทที่ต้องตรวจสอบ. |
| Dummy | อาร์กิวเมนต์จำลองสำหรับกลเม็ด SFINAE. |

### ค่าที่คืน

ค่าจะเป็น std::true_type หากมีตัวดำเนินการ == และเป็น false หากไม่มี

## System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *) ฟังก์ชัน

ฟังก์ชันช่วยเหลือเพื่อกำหนดว่าคลาสเฉพาะมีตัวดำเนินการ == หรือไม่.

```cpp
std::false_type System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *)
```

### ค่าที่คืน

ค่าจะเป็น std::true_type หากมีตัวดำเนินการ == และเป็น false หากไม่มี

## ดูเพิ่มเติม

* เนมสเปซ [System::Collections::Generic::Details](../)
* ไลบรารี [Aspose.Slides](../../)