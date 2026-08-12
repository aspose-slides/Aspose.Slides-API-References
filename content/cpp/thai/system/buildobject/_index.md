---
title: BuildObject()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างอ็อบเจกต์ด้วยการเป็นเจ้าของร่วม
type: docs
weight: 2250
url: /th/system/buildobject/
---
## System::BuildObject(Args\&&...) ฟังก์ชัน

Build an object with shared ownership.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```

### พารามิเตอร์แม่แบบ

| Parameter | คำอธิบาย |
| --- | --- |
| T | ประเภทของวัตถุที่จะสร้าง |
| Args | ประเภทของอาร์กิวเมนต์สำหรับการสร้างวัตถุ |

### อาร์กิวเมนต์

| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| args | Args\&&... | อาร์กิวเมนต์ที่จะส่งต่อไปยังคอนสตรัคเตอร์ของวัตถุ |

### ค่าที่ส่งคืน

ObjectBuilder ที่กำหนดค่าไว้สำหรับการสร้าง shared pointer
## หมายเหตุ

Creates a SharedPtr<T> and returns a builder for it 
[Object](../object/) การสร้างต้องเสร็จสิ้นด้วยการเรียก [Get()](../get/)

## ดูเพิ่มเติม

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)