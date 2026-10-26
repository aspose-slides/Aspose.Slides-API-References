---
title: operator()()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เปรียบเทียบประเภทค่าที่ใช้งานอินเทอร์เฟซ IComparable.
type: docs
weight: 1
url: /th/system.collections.generic.details/comparertype/operator_call/
---
## ComparerType::operator()(const Q\&, const Q\&) const method


เปรียบเทียบประเภทค่าที่ใช้งานอินเทอร์เฟซ [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<Q>, Q>::value||has_method_compareto<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Q | ประเภทที่ต้องการเปรียบเทียบ. |

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| a | const Q\& | ค่า LHS. |
| b | const Q\& | ค่า RHS. |

### ค่าที่ส่งคืน

เป็นจริงเมื่อ **a** ถูกพิจารณาว่าน้อยกว่า **b**, มิฉะนั้นเป็นเท็จ.

## ComparerType::operator()(const Q\&, const Q\&) const method


เปรียบเทียบประเภทค่าพื้นฐานและอ็อบเจ็กต์ที่ไม่ได้ใช้งานอินเทอร์เฟซ [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<IComparable<Q>, Q>::value||has_method_compareto<Q>::value)&&!std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Q | ประเภทที่ต้องการเปรียบเทียบ. |

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| a | const Q\& | ค่า LHS. |
| b | const Q\& | ค่า RHS. |

### ค่าที่ส่งคืน

เป็นจริงเมื่อ **a** ถูกพิจารณาว่าน้อยกว่า **b**, มิฉะนั้นเป็นเท็จ.

## ComparerType::operator()(const Q\&, const Q\&) const method


เปรียบเทียบประเภทจำนวนจุดทศนิยม.

```cpp
template<typename Q> std::enable_if<std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Q | ประเภทที่ต้องการเปรียบเทียบ. |

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| a | const Q\& | ค่า LHS. |
| b | const Q\& | ค่า RHS. |

### ค่าที่ส่งคืน

เป็นจริงเมื่อ **a** ถูกพิจารณาว่าน้อยกว่า **b**, มิฉะนั้นเป็นเท็จ.

## ดูเพิ่มเติม

* คลาส [IComparable](../../../system/icomparable/)
* โครงสร้าง [has_method_compareto](../../has_method_compareto/)
* โครงสร้าง [ComparerType](../)
* เนมสเปซ [System::Collections::Generic::Details](../../)
* ไลบรารี [Aspose.Slides](../../../)