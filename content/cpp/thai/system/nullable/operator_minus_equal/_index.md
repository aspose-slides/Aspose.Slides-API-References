---
title: operator-=()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งกลับอินสแตนซ์ของคลาส Nullable ที่แทนค่าที่เป็น null.
type: docs
weight: 248
url: /th/system/nullable/operator_minus_equal/
---
## Nullable::operator-=(T1) เมธอด


ส่งกลับอินสแตนซ์ของคลาส [Nullable](../) ที่แทนค่าที่เป็น null.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## Nullable::operator-=(const T1\&) เมธอด


ใช้ [operator-=()](./) กับค่าที่แทนโดยอ็อบเจกต์ปัจจุบันโดยใช้ค่าที่ระบุเป็นอาร์กิวเมนต์ด้านขวา.

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```


### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| T1 | ชนิดของค่าที่ใช้เป็นค่าข้างขวาของ [operator-=()](./) |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | การอ้างอิงคงที่ไปยังค่าที่ใช้เป็นค่าข้างขวาของ [operator-=()](./) ที่ใช้กับค่าที่แทนโดยอ็อบเจกต์ปัจจุบัน. |

### ค่าที่ส่งกลับ

อ้างอิงถึงตัวเอง

## Nullable::operator-=(const Nullable\<T1\>\&) เมธอด


ใช้ [operator-=()](./) กับค่าที่แทนโดยอ็อบเจกต์ปัจจุบันโดยใช้ค่าที่แทนโดยอ็อบเจกต์ [Nullable](../) ที่ระบุเป็นอาร์กิวเมนต์ด้านขวา.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```


### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| T1 | ชนิดพื้นฐานของอ็อบเจกต์ [Nullable](../) ที่ค่าที่แทนโดยอ็อบเจกต์นั้นใช้เป็นอาร์กิวเมนต์ด้านขวาของ [operator-=()](./) |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | การอ้างอิงคงที่ไปยังอ็อบเจกต์ [Nullable](../) ที่ค่าที่แทนโดยอ็อบเจกต์นั้นใช้เป็นอาร์กิวเมนต์ด้านขวาของ [operator-=()](./) ที่ใช้กับค่าที่แทนโดยอ็อบเจกต์ปัจจุบัน. |

### ค่าที่ส่งกลับ

อ้างอิงถึงตัวเอง

## ดูเพิ่มเติม

* Class [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)