---
title: operator-()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ลบค่าที่ nullable และค่า null-pointer.
type: docs
weight: 222
url: /th/system/nullable/operator_minus/
---
## Nullable::operator-(T1) const method

ลบค่าที่ nullable และค่า null-pointer

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | ประเภทของออเปอแรนด์ทางขวา, ควรเป็น nullptr_t. |

### Return Value

วัตถุ [Nullable](../) ว่าง

## Nullable::operator-(const T1\&) const method

ลบค่าที่ nullable กับค่าที่ไม่ใช่ nullable

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator-(const T1 &other) const -> Nullable<decltype(get_Value() - other)>
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | ประเภทของออเปอแรนด์ทางขวา. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | ค่าที่จะลบ. |

### Return Value

ผลลัพธ์ของการลบ

## Nullable::operator-(const Nullable\<T1\>\&) const method

ลบค่าที่ nullable

```cpp
template<typename T1> auto System::Nullable<T>::operator-(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value() - other.get_Value())>
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | ประเภทของออเปอแรนด์ทางขวา. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | ค่าที่จะลบ. |

### Return Value

ผลลัพธ์ของการลบ

## ดูเพิ่มเติม

* คลาส [Nullable](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)