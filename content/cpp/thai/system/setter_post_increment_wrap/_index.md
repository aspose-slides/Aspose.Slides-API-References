---
title: setter_post_increment_wrap()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตัวแปลจะทำการแปลการแสดงผลเพิ่มค่าหลังของ C# ที่อ้างอิง property ของคลาสซึ่งมีการกำหนด setter และ getter ให้เป็นการเรียกใช้ฟังก์ชันนี้
type: docs
weight: 2848
url: /th/system/setter_post_increment_wrap/
---
## System::setter_post_increment_wrap(T(*)(), void(*)(T)) ฟังก์ชัน

Translator แปลการแสดงผลเพิ่มค่าหลังของ C# ที่อ้างอิง property ของคลาสที่กำหนด setter และ getter ไว้ ให้เป็นการเรียกใช้ฟังก์ชันนี้

```cpp
template<typename T> T System::setter_post_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของคุณสมบัติ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pGetter | T(*)() | ตัวชี้ฟังก์ชันชี้ไปยังฟังก์ชัน getter ฟรีของคุณสมบัติ |
| pSetter | void(*)(T) | ตัวชี้ฟังก์ชันชี้ไปยังฟังก์ชัน setter ฟรีของคุณสมบัติ |

### ค่าที่คืน

ค่าของคุณสมบัติก่อนการเพิ่มค่า

## System::setter_post_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) ฟังก์ชัน

Translator แปลการแสดงผลเพิ่มค่าหลังของ C# ที่อ้างอิง property ของอินสแตนซ์ที่กำหนด setter และ getter ไว้ ให้เป็นการเรียกใช้ฟังก์ชันนี้ (overload สำหรับ getter ที่ไม่เป็น const)

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของคุณสมบัติ |
| Host | - คลาสของอินสแตนซ์ที่ต้องการแก้ไข |
| HostGet | - Host เอง หรือฐานคลาสที่กำหนด getter ของคุณสมบัติ |
| HostSet | - Host เอง หรือฐานคลาสที่กำหนด setter ของคุณสมบัติ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| host | Host *const | อินสแตนซ์ที่ใช้เรียก getter และ setter |
| pGetter | T(HostGet::*)() | ตัวชี้ฟังก์ชันชี้ไปยังฟังก์ชัน getter ของคุณสมบัติ |
| pSetter | void(HostSet::*)(T) | ตัวชี้ฟังก์ชันชี้ไปยังฟังก์ชัน setter ของคุณสมบัติ |

### ค่าที่คืน

ค่าของคุณสมบัติก่อนการเพิ่มค่า

## System::setter_post_increment_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) ฟังก์ชัน

Translator แปลการแสดงผลเพิ่มค่าหลังของ C# ที่อ้างอิง property ของอินสแตนซ์ที่กำหนด setter และ getter ไว้ ให้เป็นการเรียกใช้ฟังก์ชันนี้ (overload สำหรับ getter ที่เป็น const)

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของคุณสมบัติ |
| Host | - คลาสของอินสแตนซ์ที่ต้องการแก้ไข |
| HostConstGet | - Host เอง หรือฐานคลาสที่กำหนด getter ของคุณสมบัติ |
| HostSet | - Host เอง หรือฐานคลาสที่กำหนด setter ของคุณสมบัติ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| host | Host *const | อินสแตนซ์ที่ใช้เรียก getter และ setter |
| pGetter | T(HostConstGet::*)() const | ตัวชี้ฟังก์ชันชี้ไปยังฟังก์ชัน getter ของคุณสมบัติ |
| pSetter | void(HostSet::*)(T) | ตัวชี้ฟังก์ชันชี้ไปยังฟังก์ชัน setter ของคุณสมบัติ |

### ค่าที่คืน

ค่ของคุณสมบัติก่อนการเพิ่มค่า

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)