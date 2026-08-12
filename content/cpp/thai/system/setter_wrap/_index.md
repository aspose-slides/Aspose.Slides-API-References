---
title: setter_wrap()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: โอเวอร์โหลดสำหรับฟังก์ชัน setter แบบสถิตย์ที่มีการแปลงประเภท.
type: docs
weight: 2822
url: /th/system/setter_wrap/
---
## System::setter_wrap(void(*)(T2), T) ฟังก์ชัน

Overload สำหรับฟังก์ชัน setter แบบสถิตย์ที่มีการแปลงประเภท.

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```

### พารามิเตอร์แบบแม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทค่า. |
| T2 | ชนิดที่คาดว่าจะรับโดยฟังก์ชัน setter. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pSetter | void(*)(T2) | อ้างอิงฟังก์ชัน setter แบบสถิตย์. |
| value | T | ค่าที่จะตั้งค่า. |

### ค่าที่ส่งคืน

ตั้งค่า.

## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) ฟังก์ชัน

Overload สำหรับฟังก์ชัน setter ของอินสแตนซ์ที่มีการแปลงประเภท.

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```

### พารามิเตอร์แบบแม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทค่า. |
| T2 | ชนิดที่คาดว่าจะรับโดยฟังก์ชัน setter. |
| Host | ประเภทอินสแตนซ์. |
| HostSet | - Host เอง หรือชนิดพื้นฐานของมัน ที่กำหนด setter ของคุณสมบัติ. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| host | Host *const | [Object](../object/) เพื่อเรียกฟังก์ชัน setter สำหรับ. |
| pSetter | void(HostSet::*)(T2) | อ้างอิงฟังก์ชัน setter. |
| value | T | ค่าที่จะตั้งค่า. |

### ค่าที่ส่งคืน

ตั้งค่า.

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)