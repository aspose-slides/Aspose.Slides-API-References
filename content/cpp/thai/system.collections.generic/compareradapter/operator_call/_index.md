---
title: operator()()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: ฟังก์ชันการเปรียบเทียบสำหรับประเภทที่มี operator < พร้อมใช้งาน.
type: docs
weight: 27
url: /th/system.collections.generic/compareradapter/operator_call/
---
## ComparerAdapter::operator()(const Q\&, const Q\&) const เมธอด


[Comparison](../../../system/comparison/) ฟังก์ชันสำหรับประเภทที่มี operator < พร้อมใช้งาน.

```cpp
template<typename Q> std::enable_if<detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| Q | Type being compared; template for type conversion availability. |

### พารามิเตอร์

| Parameter | Type | Description |
| --- | --- | --- |
| x | const Q\& | First value to compare. |
| y | const Q\& | Second value to compare. |

### ค่าที่ส่งคืน

True if **x** is considered less than **y**, false otherwise.

## ComparerAdapter::operator()(const Q\&, const Q\&) const เมธอด


[Comparison](../../../system/comparison/) ฟังก์ชันสำหรับประเภทที่ไม่มี operator < ไม่พร้อมใช้งาน.

```cpp
template<typename Q> std::enable_if<!detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| Q | Type being compared; template for type conversion availability. |

### พารามิเตอร์

| Parameter | Type | Description |
| --- | --- | --- |
| x | const Q\& | First value to compare. |
| y | const Q\& | Second value to compare. |

### ค่าที่ส่งคืน

True หากตัวเปรียบเทียบถูกตั้งค่าและ **x** is considered less than **y**, false otherwise.

## ดูเพิ่มเติม

* Struct [ComparerAdapter](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)