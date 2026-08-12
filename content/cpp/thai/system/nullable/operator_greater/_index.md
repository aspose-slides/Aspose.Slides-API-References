---
title: operator>()
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: จะคืนค่า false เสมอ.
type: docs
weight: 157
url: /th/system/nullable/operator_greater/
---
## Nullable::operator>(std::nullptr_t) const เมธอด

จะคืนค่า false เสมอ.

```cpp
bool System::Nullable<T>::operator>(std::nullptr_t) const
```

## Nullable::operator>(const T1\&) const เมธอด

กำหนดว่าค่าที่แทนโดยอ็อบเจกต์ปัจจุบันมากกว่าค่าที่ระบุหรือไม่โดยการใช้ [operator>()](./) กับค่าทั้งสองนี้.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>(const T1 &other) const
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| T1 | ประเภทของค่าที่จะเปรียบเทียบกับ |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | การอ้างอิงคงที่ไปยังค่าที่จะเปรียบเทียบกับ |

### ค่าที่ส่งคืน

เป็นค่า true หากค่าที่แทนโดยอ็อบเจกต์ปัจจุบันมากกว่าค่าที่ระบุ มิฉะนั้น - false

## Nullable::operator>(const Nullable\<T1\>\&) const เมธอด

กำหนดว่าค่าที่แทนโดยอ็อบเจกต์ปัจจุบันมากกว่าค่าที่แทนโดยอ็อบเจกต์ [Nullable](../) ที่ระบุหรือไม่โดยการใช้ [operator>()](./) กับค่าทั้งสองนี้.

```cpp
template<typename T1> bool System::Nullable<T>::operator>(const Nullable<T1> &other) const
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| T1 | ประเภทพื้นฐานของอ็อบเจกต์ [Nullable](../) ที่จะเปรียบเทียบกับ |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | การอ้างอิงคงที่ไปยังอ็อบเจกต์ [Nullable](../) ที่จะเปรียบเทียบกับ |

### ค่าที่ส่งคืน

เป็นค่า true หากค่าที่แทนโดยอ็อบเจกต์ปัจจุบันมากกว่าค่าที่แทนโดยอ็อบเจกต์ [Nullable](../) ที่ระบุ มิฉะนั้น - false

## ดูเพิ่มเติม

* คลาส [Nullable](../)
* โครงสร้าง [IsNullable](../../isnullable/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)