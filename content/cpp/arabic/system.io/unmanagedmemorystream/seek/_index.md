---
title: Seek()
second_title: مرجع API Aspose.Slides للغة C++
description: يضبط موضع الدفق الممثل بواسطة الكائن الحالي.
type: docs
weight: 157
url: /ar/system.io/unmanagedmemorystream/seek/
---
## UnmanagedMemoryStream::Seek(int64_t, SeekOrigin) طريقة

يضبط موضع الدفق المُمثل بواسطة الكائن الحالي.

```cpp
virtual int64_t System::IO::UnmanagedMemoryStream::Seek(int64_t offset, SeekOrigin loc) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| offset | **int64_t** | الإزاحة بالبايت نسبةً إلى موضع محدد بواسطة **origin** |
| loc | [SeekOrigin](../../seekorigin/) | يحدد الموضع الذي تُحسب منه الإزاحة والاتجاه الذي تُحسب نحوه |

### قيمة الإرجاع

الموضع الجديد للدفق

## انظر أيضًا

* Enum [SeekOrigin](../../seekorigin/)
* Class [UnmanagedMemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)