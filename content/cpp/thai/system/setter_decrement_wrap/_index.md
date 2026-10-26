---
title: setter_decrement_wrap()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตัวแปลจะแปลงการแสดงผลการหักลบก่อนของ C# ที่กำหนดให้กับ property ของคลาสที่มีการกำหนด setter และ getter ให้เป็นการเรียกใช้ฟังก์ชันนี้.
type: docs
weight: 2861
url: /th/system/setter_decrement_wrap/
---
## System::setter_decrement_wrap(T(*)(), void(*)(T)) ฟังก์ชัน

ตัวแปลจะเปลี่ยนการแสดงผลการหักลบก่อนของ C# ที่กำหนดให้กับ property ของคลาสซึ่งมีการกำหนด setter และ getter ให้เป็นการเรียกใช้ฟังก์ชันนี้

```cpp
template<typename T> T System::setter_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของ property |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| pGetter | T(*)() | ตัวชี้ฟังก์ชันที่ชี้ไปยังฟังก์ชันฟรี getter ของ property |
| pSetter | void(*)(T) | ตัวชี้ฟังก์ชันที่ชี้ไปยังฟังก์ชันฟรี setter ของ property |

### ค่าที่คืน

ค่ของ property ก่อนทำการเพิ่ม

## System::setter_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) ฟังก์ชัน

ตัวแปลจะเปลี่ยนการแสดงผลการหักลบก่อนของ C# ที่กำหนดให้กับ property ของอินสแตนซ์ซึ่งมีการกำหนด setter และ getter ให้เป็นการเรียกใช้ฟังก์ชันนี้ (overload สำหรับ getter ที่ไม่เป็น const)

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของ property |
| Host | - คลาสของอินสแตนซ์ที่ต้องการปรับแก้ |
| HostGet | - Host เอง หรือประเภทฐานของมัน ที่กำหนด getter ของ property |
| HostSet | - Host เอง หรือประเภทฐานของมัน ที่กำหนด setter ของ property |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| host | Host *const | อินสแตนซ์ที่จะเรียกใช้ getters และ setters สำหรับ |
| pGetter | T(HostGet::*)() | ตัวชี้ฟังก์ชันที่ชี้ไปยังฟังก์ชัน getter ของ property |
| pSetter | void(HostSet::*)(T) | ตัวชี้ฟังก์ชันที่ชี้ไปยังฟังก์ชัน setter ของ property |

### ค่าที่คืน

ค่ของ property ก่อนทำการเพิ่ม

## System::setter_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) ฟังก์ชัน

ตัวแปลจะเปลี่ยนการแสดงผลการหักลบก่อนของ C# ที่กำหนดให้กับ property ของอินสแตนซ์ซึ่งมีการกำหนด setter และ getter ให้เป็นการเรียกใช้ฟังก์ชันนี้ (overload สำหรับ getter ที่เป็น const)

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของ property |
| Host | - คลาสของอินสแตนซ์ที่ต้องการปรับแก้ |
| HostConstGet | - Host เอง หรือประเภทฐานของมัน ที่กำหนด getter ของ property |
| HostSet | - Host เอง หรือประเภทฐานของมัน ที่กำหนด setter ของ property |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| host | Host *const | อินสแตนซ์ที่จะเรียกใช้ getters และ setters สำหรับ |
| pGetter | T(HostConstGet::*)() const | ตัวชี้ฟังก์ชันที่ชี้ไปยังฟังก์ชัน getter ของ property |
| pSetter | void(HostSet::*)(T) | ตัวชี้ฟังก์ชันที่ชี้ไปยังฟังก์ชัน setter ของ property |

### ค่าที่คืน

ค่ของ property ก่อนทำการเพิ่ม

## ดูเพิ่มเติม

* เนมส페ซ [System](../)
* ไลบรารี [Aspose.Slides](../../)