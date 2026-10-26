---
title: operator+()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: ส่งคืนอินสแตนซ์ที่สร้างจากค่าเริ่มต้นของคลาส Nullable<T>.
type: docs
weight: 209
url: /th/system/nullable/operator_plus/
---
## Nullable::operator+(std::nullptr_t) const เมธอด

Returns a default constructed instance of Nullable<T> คลาส.

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Nullable::operator+(const T1\&) const เมธอด

Sums nullable and non-nullable values.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator+(const T1 &other) const -> Nullable<decltype(get_Value()+other)>
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทตัวดำเนินการขวา. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| other | const T1\& | ค่าที่จะเพิ่ม. |

### ค่าที่คืนค่า

ผลลัพธ์ของการบวก.

## Nullable::operator+(const Nullable\<T1\>\&) const เมธอด

Sums nullable values.

```cpp
template<typename T1> auto System::Nullable<T>::operator+(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value()+other.get_Value())>
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทตัวดำเนินการขวา. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | ค่าที่จะเพิ่ม. |

### ค่าที่คืนค่า

ผลลัพธ์ของการบวก.

## ดูเพิ่มเติม

* คลาส [Nullable](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)