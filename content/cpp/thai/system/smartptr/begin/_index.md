---
title: begin()
second_title: การอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตัวเข้าถึงสำหรับเมธอด begin() ของคอลเลกชันที่อยู่ภายใต้. จะคอมไพล์ได้ก็ต่อเมื่อ SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด begin().
type: docs
weight: 378
url: /th/system/smartptr/begin/
---
## SmartPtr::begin() เมธอด


ตัวเข้าถึงสำหรับเมธอด [begin()](./) ของคอลเลกชันที่อยู่ภายใต้. จะคอมไพล์ได้ก็ต่อเมื่อ SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [begin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() -> decltype(std::declval<Q>().begin())
```


### ค่าที่ส่งกลับ

อิเทอเรเตอร์ไปยังจุดเริ่มต้นของคอลเลกชัน

## SmartPtr::begin() const เมธอด


ตัวเข้าถึงสำหรับเมธอด [begin()](./) ของคอลเลกชันที่อยู่ภายใต้. จะคอมไพล์ได้ก็ต่อเมื่อ SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด [begin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() const -> decltype(std::declval<const Q>().begin())
```


### ค่าที่ส่งกลับ

อิเทอเรเตอร์ไปยังจ점เริ่มต้นของคอลเลกชัน

## ดูเพิ่มเติม

* คลาส [SmartPtr](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)