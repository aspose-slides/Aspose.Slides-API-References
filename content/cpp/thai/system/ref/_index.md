---
title: Ref()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: สร้างการอ้างอิงถึงอ็อบเจกต์ DynamicWeakPtr ใช้โดยตัวแปลเมื่อส่งอาร์กิวเมนต์ของฟังก์ชันโดยอ้างอิง
type: docs
weight: 2458
url: /th/system/ref/
---
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) ฟังก์ชัน

สร้างการอ้างอิงถึงวัตถุ [DynamicWeakPtr](../dynamicweakptr/) ใช้โดยตัวแปลเมื่อส่งอาร์กิวเมนต์ของฟังก์ชันโดยอ้างอิง

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของพอยน์ที |
| trunkMode | โหมดของสมาร์ทพอยน์เตอร์เอง |
| weakLeafs | ดัชนีของอากิวเมนต์เทมเพลตที่ต้องเรียกเมธอด SetTemplateWeakPtr |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| ptr | [DynamicWeakPtr](../dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\& | สมาร์ทพอยน์เตอร์ที่ต้องสร้างการอ้างอิงถึง |

### ค่าที่ส่งกลับ

สมาร์ทพอยน์เตอร์อ้างอิง

## System::Ref(T\&) ฟังก์ชัน

ฟังก์ชันช่วยเหลือสำหรับรับการอ้างอิงถึงอ็อบเจกต์ ใช้เพื่อรับประกันว่า [System::DynamicWeakPtr](../dynamicweakptr/) จะอัพเดตอ็อบเจกต์ที่อ้างอิงหลังจากการกำหนดค่า

```cpp
template<typename T> T & System::Ref(T &value)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทที่ต้องสร้างการอ้างอิงถึง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | T\& | ค่าที่ต้องสร้างการอ้างอิงถึง |

### ค่าที่ส่งกลับ

การอ้างอิงถึงค่าที่ส่งให้ฟังก์ชันนี้

## ดูเพิ่มเติม

* คลาส [DynamicWeakPtr](../dynamicweakptr/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)