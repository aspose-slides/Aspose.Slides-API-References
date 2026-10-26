---
title: IsStringPointer
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เทคนิครูปแบบเพื่อตรวจสอบว่าชนิดเป็นตัวชี้ไปยังสตริงอักขระหรือไม่.
type: docs
weight: 1743
url: /th/system/isstringpointer/
---
## IsStringPointer struct

เทคนิครูปแบบเพื่อตรวจสอบว่าชนิดเป็นตัวชี้ไปยังสตริงอักขระหรือไม่.

```cpp
template<typename T,typename CharT>class IsStringPointer : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_pointer<T>::value>
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดที่ตรวจสอบ |
| CharT | ชนิดอักขระที่จะตรวจสอบ |

## ดูเพิ่มเติม

* เนมส페ซ [System](../)
* ไลบรารี [Aspose.Slides](../../)