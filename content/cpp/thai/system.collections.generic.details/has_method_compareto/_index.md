---
title: has_method_compareto
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "ตรวจสอบว่าเมธอด CompareTo มีอยู่ในประเภทที่ระบุหรือไม่ หากมี จะสืบทอดจาก std::true_type, หากไม่มีจะสืบทอดจาก std::false_type สามารถใช้ใน std::enable_if ได้."
type: docs
weight: 170
url: /th/system.collections.generic.details/has_method_compareto/
---
## has_method_compareto struct

ตรวจสอบว่าเมธอด CompareTo มีอยู่ในประเภทที่ระบุหรือไม่ หากมี จะสืบทอดจาก std::true_type, หากไม่มีจะสืบทอดจาก std::false_type สามารถใช้ใน std::enable_if ได้

```cpp
template<typename T,typename Sfinae>class has_method_compareto : public std::false_type
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทเพื่อเช็กว่ามีเมธอด Equals หรือไม่ |
| Sfinae | อาร์กิวเมนต์เทมเพลตอย่างเป็นทางการเพื่อให้ SFINAE ทำงาน |

## ดูเพิ่มเติม

* เนมสเปซ [System::Collections::Generic::Details](../)
* ไลบรารี [Aspose.Slides](../../)