---
title: has_print_to_method
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "ตรวจสอบการ overload ของฟังก์ชัน PrintTo ที่รับประเภทที่กำหนดเป็นอาร์กิวเมนต์แรก หากมีการ overload จะสืบทอดจาก std::true_type, หากไม่มีจะสืบทอดจาก std::false_type."
type: docs
weight: 27
url: /th/system.testpredicates.typetraits/has_print_to_method/
---
## has_print_to_method struct

ตรวจสอบการ overload ของฟังก์ชัน PrintTo ที่รับประเภทที่กำหนดเป็นอาร์กิวเมนต์แรก หากมีการ overload จะสืบทอดจาก std::true_type, หากไม่มีจะสืบทอดจาก std::false_type.

```cpp
template<typename T,typename Enable>class has_print_to_method : public std::false_type
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทที่ต้องการตรวจสอบ. |
| Enable | อาร์กิวเมนต์รูปแบบสำหรับทำงานของ SFINAE. |

## ดูเพิ่มเติม

* เนมสเปซ [System::TestPredicates::TypeTraits](../)
* ไลบรารี [Aspose.Slides](../../)