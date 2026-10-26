---
title: IsWeakPtr
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "คลาส Traits เพื่อตรวจสอบว่าคลาสเฉพาะเป็น specialization ของ System::WeakPtr. ไม่ได้ตรวจสอบว่าตัวอย่างอยู่ในโหมด weak จริงหรือไม่."
type: docs
weight: 1756
url: /th/system/isweakptr/
---
## IsWeakPtr struct

Traits คลาสเพื่อเช็คว่า คลาสเฉพาะเป็น specialization ของ [System::WeakPtr](../weakptr/). ไม่ได้ตรวจสอบว่าตัวอย่างอยู่ในโหมด weak จริงหรือไม่.

```cpp
template<class T>class IsWeakPtr : public System::detail::is_a<T, System::WeakPtr>
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทที่ทดสอบ. |

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)