---
title: has_method_compareto_shared_ptr
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ตรวจสอบว่าเมธอด CompareTo(SharedPtr<T>) มีอยู่ในประเภทที่ระบุหรือไม่ หากมี จะสืบทอดจาก std::true_type มิฉะนั้นจะสืบทอดจาก std::false_type สามารถใช้ใน std::enable_if."
type: docs
weight: 183
url: /th/system.collections.generic.details/has_method_compareto_shared_ptr/
---
## has_method_compareto_shared_ptr struct


ตรวจสอบว่าเมธอด CompareTo(SharedPtr<T>) มีอยู่ในประเภทที่ระบุหรือไม่ หากมีจะสืบทอดจาก std::true_type มิฉะนั้นจะสืบทอดจาก std::false_type สามารถใช้ใน std::enable_if

```cpp
template<typename T,typename Sfinae>class has_method_compareto_shared_ptr : public std::false_type
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทที่ตรวจสอบว่าเมธอด Equals มีอยู่หรือไม่ |
| Sfinae | อาร์กิวเมนต์เทมเพลตแบบฟอร์มสำหรับทำงานของ SFINAE |

## ดูเพิ่ม

* เนมสเปซ [System::Collections::Generic::Details](../)
* ไลบรารี [Aspose.Slides](../../)