---
title: ToByteArray()
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: يقوم بتحويل السلسلة أو الجزء الفرعي إلى مصفوفة من البايتات.
type: docs
weight: 508
url: /ar/system/string/tobytearray/
---
## String::ToByteArray(int32_t, int32_t, bool) const طريقة

تحول السلسلة أو الجزء الفرعي إلى مصفوفة من البايتات.

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=1) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | **int32_t** | مؤشر بداية الجزء الفرعي. |
| length | **int32_t** | طول الجزء الفرعي. |
| LE | **bool** | إذا كان true، يتم تشفير الأحرف باستخدام ترتيب بايت صغير (little endian)؛ وإلا يتم استخدام ترتيب بايت كبير (big endian). |

### قيمة الإرجاع

[Array](../../array/) يحتوي على بايتات تمثل أحرف السلسلة.

## انظر أيضًا

* Typedef [ArrayPtr](../../arrayptr/)
* الفئة [String](../)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)