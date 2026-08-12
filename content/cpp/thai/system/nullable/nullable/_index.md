---
title: Nullable()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างอินสแตนซ์ที่แทนค่าที่เป็น null.
type: docs
weight: 1
url: /th/system/nullable/nullable/
---
## Nullable::Nullable() คอนสตรัคเตอร์

สร้างอินสแตนซ์ที่แทนค่าที่เป็น null

```cpp
System::Nullable<T>::Nullable()
```

## Nullable::Nullable(std::nullptr_t) คอนสตรัคเตอร์

สร้างอินสแตนซ์ที่แทนค่า null

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```

## Nullable::Nullable(const T1\&) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของคลาส [Nullable](../) ที่แทนค่าที่ระบุ (แปลงหากจำเป็น) เป็นค่าของประเภทพื้นฐาน T

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทของค่าที่ระบุ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const T1\& | การอ้างอิงค่าสต็อตที่เป็นค่าคงที่ของค่าที่จะถูกแทนโดยอ็อบเจกต์ [Nullable](../) ที่สร้างใหม่ |

## Nullable::Nullable(const Nullable\<T1\>\&) คอนสตรัคเตอร์

สร้างอินสแตนซ์ที่แทนค่าที่ถูกแทนโดยวัตถุ [Nullable](../) ที่ระบุ วัตถุ nullable ที่ระบุอาจแทนค่าประเภทที่แตกต่างจากประเภทพื้นฐานของอินสแตนซ์ที่สร้าง ซึ่งในกรณีนี้ค่าที่แทนจะถูกแปลงเป็นค่าประเภท T

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทของค่าที่แทนโดยวัตถุ [Nullable](../) ที่ระบุ |

## ดูเพิ่มเติม

* คลาส [Nullable](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)