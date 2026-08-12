---
title: IsBoxable
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: พรีดิเคตเทมเพลตที่ตรวจสอบว่าการบรรจุของประเภทที่ระบุได้รับการสนับสนุนหรือไม่
type: docs
weight: 1665
url: /th/system/isboxable/
---
## IsBoxable struct

พรีดิเคตเทมเพลตที่ตรวจสอบว่าการ boxing ของประเภทที่ระบุได้รับการสนับสนุนหรือไม่.

```cpp
template<typename T>class IsBoxable : public std::integral_constant<bool, std::is_base_of<Details::BoxableObjectBase, T>::value||std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทที่ต้องการตรวจสอบ |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)