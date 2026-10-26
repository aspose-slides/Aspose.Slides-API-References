---
title: STDIOStreamWrappingMode
second_title: مرجع API Aspose.Slides للغة C++
description: "يحدد نمط عمليات الإدخال/الإخراج التي سيقوم المغلفون بأدائها على تدفقات تشبه std::iostreams."
type: docs
weight: 573
url: /ar/system.io/stdiostreamwrappingmode/
---
## STDIOStreamWrappingMode enum

يحدد نمط عمليات الإدخال/الإخراج التي سيقوم بها المغلفون على تدفقات تشبه std::iostreams.

```cpp
enum class STDIOStreamWrappingMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Binary | 0 | وضع يسمح لعمليات الإدخال بفك ترميز بيانات التدفق من نوع char_type إلى بايتات، وتشفير البايتات إلى بيانات من نوع char_type لعمليات الإخراج. |
| Conversion | 1 | وضع يسمح لعمليات الإدخال بتحويل بيانات التدفق من نوع char_type إلى نوع **uint8_t** والعكس للعميات الإخراجية. |

## انظر أيضا

* النطاق [System::IO](../)
* المكتبة [Aspose.Slides](../../)