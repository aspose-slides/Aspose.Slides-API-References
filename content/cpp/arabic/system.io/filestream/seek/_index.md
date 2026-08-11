---
title: Seek()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضبط موضع الدفق الممثل بالكائن الحالي.
type: docs
weight: 209
url: /ar/system.io/filestream/seek/
---
## FileStream::Seek(int64_t, SeekOrigin) طريقة

يضبط موضع الدفق الذي يمثله الكائن الحالي.

```cpp
int64_t System::IO::FileStream::Seek(int64_t offset, SeekOrigin origin) override
```

### المعلمات

| معلمة | نوع | وصف |
| --- | --- | --- |
| offset | **int64_t** | الإزاحة البايتية بالنسبة لموضع محدد بواسطة **origin**. |
| origin | [SeekOrigin](../../seekorigin/) | يحدد الموضع الذي تُحسب منه الإزاحة والاتجاه الذي تُحسب إليه الإزاحة. |

### قيمة الإرجاع

الموضع الجديد للدفق.

## انظر أيضًا

* تعداد [SeekOrigin](../../seekorigin/)
* فئة [FileStream](../)
* نطاق [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)