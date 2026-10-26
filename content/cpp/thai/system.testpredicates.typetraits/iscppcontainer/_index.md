---
title: IsCppContainer
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: "ตรวจสอบว่าประเภทที่ระบุเป็นคอนเทนเนอร์สไตล์ STL หรือไม่ เพื่อทำเช่นนี้ จะตรวจสอบว่ามีสมาชิกประเภท iterator และ const_iterator หรือไม่ หากทั้งสองมีอยู่ จะสืบทอด std::true_type มิฉะนั้นจะสืบทอด std::false_type."
type: docs
weight: 40
url: /th/system.testpredicates.typetraits/iscppcontainer/
---
## IsCppContainer struct

ตรวจสอบว่าประเภทที่ระบุเป็นคอนเทนเนอร์สไตล์ STL หรือไม่ เพื่อตรวจสอบนี้ จะตรวจสอบว่ามีสมาชิกประเภท iterator และ const_iterator หรือไม่ หากทั้งสองมีอยู่ จะสืบทอด std::true_type มิฉะนั้นจะสืบทอด std::false_type.

```cpp
template<typename T,typename Enable>class IsCppContainer : public std::false_type
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทที่ต้องการตรวจสอบ. |
| Enable | อากิวเมนต์แบบฟอร์มสำหรับทำให้ SFINAE ทำงาน. |

## ดูเพิ่มเติม

* เนมสเปซ [System::TestPredicates::TypeTraits](../)
* ไลบรารี [Aspose.Slides](../../)