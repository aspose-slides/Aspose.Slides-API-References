---
title: cbegin()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ตัวเข้าถึงสำหรับเมธอด cbegin() ของคอลเลกชันพื้นฐาน จะคอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นประเภทพิเศษที่มีเมธอด cbegin().
type: docs
weight: 404
url: /th/system/smartptr/cbegin/
---
## SmartPtr::cbegin() const เมธอด


ตัวเข้าถึงสำหรับเมธอด [cbegin()](./) ของคอลเลกชันพื้นฐาน. จะคอมไพล์ได้เฉพาะเมื่อ SmartPtr_ เป็นชนิดพิเศษที่มีเมธอด [cbegin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::cbegin() const -> decltype(std::declval<const Q>().cbegin())
```


### ค่าที่คืนกลับ

iterator ไปยังจุดเริ่มต้นของคอลเลกชัน

## ดูเพิ่มเติม

* คลาส [SmartPtr](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)