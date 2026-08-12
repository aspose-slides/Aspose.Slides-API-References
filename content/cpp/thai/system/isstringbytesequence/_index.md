---
title: IsStringByteSequence
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เทมเพลตแมจิกเพื่อตรวจสอบว่าชนิดเป็นลำดับของอักขระสตริงหรือไม่.
type: docs
weight: 1717
url: /th/system/isstringbytesequence/
---
## IsStringByteSequence โครงสร้าง

Template magic to check if a type is a sequence of string characters.

```cpp
template<typename T,typename CharT>class IsStringByteSequence : public std::integral_constant<bool, std::is_same<std::remove_const<std::remove_pointer<std::decay<T>::type>::type>::type, CharT>::value>
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทที่ตรวจสอบ. |
| CharT | ประเภทอักขระสำหรับตรวจสอบ. |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)