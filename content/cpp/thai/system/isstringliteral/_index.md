---
title: IsStringLiteral
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เทมเพลตมายากลเพื่อตรวจสอบว่าชนิดเป็นสตริงลิเทอรัลหรือไม่.
type: docs
weight: 1730
url: /th/system/isstringliteral/
---
## IsStringLiteral struct

คมนาคมของเทมเพลตเพื่อเช็คว่าชนิดเป็นสตริงลิเทอรัลหรือไม่.

```cpp
template<typename T,typename CharT>class IsStringLiteral : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_array<T>::value>
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทที่ตรวจสอบ. |
| CharT | ประเภทอักขระที่ต้องตรวจสอบ. |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)