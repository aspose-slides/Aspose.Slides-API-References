---
title: InitObject()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เริ่มการกำหนดค่าเริ่มต้นของอ็อบเจกต์ด้วยการเป็นเจ้าของแบบแชร์
type: docs
weight: 2263
url: /th/system/initobject/
---
## System::InitObject(const SharedPtr\<T\>\&) ฟังก์ชัน

เริ่มการกำหนดค่าเริ่มต้นของอ็อบเจกต์ด้วยการเป็นเจ้าของแบบแชร์

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| T | ประเภทของอ็อบเจกต์ที่ต้องกำหนดค่าเริ่มต้น |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | [Object](../object/) เพื่อกำหนดค่าเริ่มต้น |

### ค่าที่ส่งกลับ

ObjectBuilder ที่กำหนดค่าไว้สำหรับการสร้าง shared pointer
## หมายเหตุ



[Object](../object/) การกำหนดค่าเริ่มต้นต้องเสร็จสิ้นด้วยการเรียก [Get()](../get/) 

## ดูเพิ่มเติม

* Typedef [SharedPtr](../sharedptr/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)