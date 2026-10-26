---
title: TryGetBuffer()
second_title: مرجع API Aspose.Slides للغة C++
description: يعيد مصفوفة البايتات غير الموقعة التي تم إنشاء هذا الدفق منها.
type: docs
weight: 170
url: /ar/system.io/memorystream/trygetbuffer/
---
## MemoryStream::TryGetBuffer(ArraySegment\<uint8_t\>\&) طريقة

يُرجع مصفوفة من البايتات غير الموقعة التي تم إنشاء هذا الدفق منها.

```cpp
bool System::IO::MemoryStream::TryGetBuffer(ArraySegment<uint8_t> &buffer)
```

### وسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| buffer | [ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\& | مصفوفة بايت - معامل إخراج. عندما تُرجع هذه الطريقة true، مقطع مصفوفة البايت الذي تم إنشاء هذا الدفق منه؛ عندما تُرجع false، يتم ضبط هذا المعامل إلى القيمة الافتراضية. |

### قيمة الإرجاع

True إذا نجح التحويل.

## راجع أيضاً

* الفئة [ArraySegment](../../../system/arraysegment/)
* الفئة [MemoryStream](../)
* مساحة الأسماء [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)