---
title: setter_increment_wrap()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ตัวแปลแปลงนิพจน์การเพิ่มของ C# ที่มุ่งเป้าไปยังคุณสมบัติของคลาสที่มีการกำหนด setter และ getter ให้เป็นการเรียกใช้งานฟังก์ชันนี้
type: docs
weight: 2835
url: /th/system/setter_increment_wrap/
---
## System::setter_increment_wrap(T(*)(), void(*)(T)) ฟังก์ชัน

ตัวแปลแปลงนิพจน์การเพิ่มของ C# ที่มุ่งเป้าไปยังคุณสมบัติของคลาสที่มีการกำหนด setter และ getter ให้เป็นการเรียกใช้งานฟังก์ชันนี้

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของคุณสมบัติ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pGetter | T(*)() | ตัวชี้ฟังก์ชันที่ชี้ไปยังฟังก์ชันอิสระ getter ของคุณสมบัติ |
| pSetter | void(*)(T) | ตัวชี้ฟังก์ชันที่ชี้ไปยังฟังก์ชันอิสระ setter ของคุณสมบัติ |

### ค่าที่คืนค่า

ค่าที่เพิ่มขึ้นของคุณสมบัติ

## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) ฟังก์ชัน

ตัวแปลแปลงนิพจน์การเพิ่มของ C# ที่มุ่งเป้าไปยังคุณสมบัติของคลาสที่มีการกำหนด setter และ getter ให้เป็นการเรียกใช้งานฟังก์ชันนี้

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของคุณสมบัติ |
| Host | - คลาสของอินสแตนซ์ที่จะถูกแก้ไข |
| HostGet | - Host เอง หรือประเภทฐานของมัน ที่มีการกำหนด getter ของคุณสมบัติ |
| HostSet | - Host เอง หรือประเภทฐานของมัน ที่มีการกำหนด setter ของคุณสมบัติ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| host | Host *const | ตัวชี้ไปยังอ็อบเจกต์ที่คุณสมบัติของมันจะถูกเพิ่มค่า |
| pGetter | T(HostGet::*)() | ตัวชี้ฟังก์ชันที่ชี้ไปยังเมธอด getter ของคุณสมบัติ |
| pSetter | void(HostSet::*)(T) | ตัวชี้ฟังก์ชันที่ชี้ไปยังเมธอด setter ของคุณสมบัติ |

### ค่าที่คืนค่า

ค่าที่เพิ่มขึ้นของคุณสมบัติ

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)