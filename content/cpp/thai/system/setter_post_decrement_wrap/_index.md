---
title: setter_post_decrement_wrap()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ตัวแปลแปลงนิพจน์การลดค่าหลังจากใน C# ที่มุ่งเป้าไปที่คุณสมบัติของคลาสที่มีการกำหนด setter และ getter ให้เป็นการเรียกใช้ฟังก์ชันนี้
type: docs
weight: 2874
url: /th/system/setter_post_decrement_wrap/
---
## System::setter_post_decrement_wrap(T(*)(), void(*)(T)) ฟังก์ชัน

Translator แปลนิพจน์การลดค่าหลังจากใน C# ที่มุ่งเป้าไปที่คุณสมบัติของคลาสที่มี setter และ getter กำหนดไว้ ให้เป็นการเรียกใช้ฟังก์ชันนี้.

```cpp
template<typename T> T System::setter_post_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของคุณสมบัติ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pGetter | T(*)() | พอยน์เตอร์ฟังก์ชันที่ชี้ไปยังฟังก์ชัน getter ของคุณสมบัติที่เป็นฟังก์ชันอิสระ |
| pSetter | void(*)(T) | พอยน์เตอร์ฟังก์ชันที่ชี้ไปยังฟังก์ชัน setter ของคุณสมบัติที่เป็นฟังก์ชันอิสระ |

### ค่าที่คืน

ค่าของคุณสมบัติก่อนการเพิ่มค่า

## System::setter_post_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) ฟังก์ชัน

Translator แปลนิพจน์การลดค่าหลังจากใน C# ที่มุ่งเป้าไปที่คุณสมบัติของอินสแตนซ์ที่มี setter และ getter กำหนดไว้ ให้เป็นการเรียกใช้ฟังก์ชันนี้ (เวอร์ชันที่มีการโอเวอร์โหลดสำหรับ getter ที่ไม่เป็น const).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของคุณสมบัติ |
| Host | - คลาสของอินสแตนซ์ที่ต้องการแก้ไข |
| HostGet | - Host เอง หรือชนิดฐานของมัน ที่กำหนด getter ของคุณสมบัติ |
| HostSet | - Host เอง หรือชนิดฐานของมัน ที่กำหนด setter ของคุณสมบัติ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| host | Host *const | อินสแตนซ์ที่จะเรียก getter และ setter สำหรับ |
| pGetter | T(HostGet::*)() | พอยน์เตอร์ฟังก์ชันที่ชี้ไปยังฟังก์ชัน getter ของคุณสมบัติ |
| pSetter | void(HostSet::*)(T) | พอยน์เตอร์ฟังก์ชันที่ชี้ไปยังฟังก์ชัน setter ของคุณสมบัติ |

### ค่าที่คืน

ค่าของคุณสมบัติก่อนการเพิ่มค่า

## System::setter_post_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) ฟังก์ชัน

Translator แปลนิพจน์การลดค่าหลังจากใน C# ที่มุ่งเป้าไปที่คุณสมบัติของอินสแตนซ์ที่มี setter และ getter กำหนดไว้ ให้เป็นการเรียกใช้ฟังก์ชันนี้ (เวอร์ชันที่มีการโอเวอร์โหลดสำหรับ const getter).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของคุณสมบัติ |
| Host | - คลาสของอินสแตนซ์ที่ต้องการแก้ไข |
| HostConstGet | - Host เอง หรือชนิดฐานของมัน ที่กำหนด getter ของคุณสมบัติ |
| HostSet | - Host เอง หรือชนิดฐานของมัน ที่กำหนด setter ของคุณสมบัติ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| host | Host *const | อินสแตนซ์ที่จะเรียก getter และ setter สำหรับ |
| pGetter | T(HostConstGet::*)() const | พอยน์เตอร์ฟังก์ชันที่ชี้ไปยังฟังก์ชัน getter ของคุณสมบัติ |
| pSetter | void(HostSet::*)(T) | พอยน์เตอร์ฟังก์ชันที่ชี้ไปยังฟังก์ชัน setter ของคุณสมบัติ |

### ค่าที่คืน

ค่าของคุณสมบัติก่อนการเพิ่มค่า

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)