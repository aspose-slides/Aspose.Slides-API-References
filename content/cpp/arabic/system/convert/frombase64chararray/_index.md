---
title: FromBase64CharArray()
second_title: مرجع API لبرنامج Aspose.Slides للـ C++
description: يفك شيفرة البيانات المشفرة بصيغة base-64 والممثلة كنطاق في مصفوفة الأحرف Unicode.
type: docs
weight: 53
url: /ar/system/convert/frombase64chararray/
---
## Convert::FromBase64CharArray(const ArrayPtr\<char_t\>\&, int, int) method

يفكّ شيفرة البيانات المشفرة بصيغة base-64، الممثلة كنطاق في مصفوفة من الأحرف Unicode.

```cpp
static ArrayPtr<uint8_t> System::Convert::FromBase64CharArray(const ArrayPtr<char_t> &in_array, int offset, int length)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | المصفوفة التي تحتوي على البيانات لفك الشيفرة |
| offset | int | الموضع في مصفوفة الإدخال الذي يبدأ عنده النطاق المراد فك شيفرته |
| length | int | طول النطاق المراد فك شيفرته |

### قيمة الإرجاع

مصفوفة بايتات تحتوي على البيانات التي تم فك شيفرتها

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../arrayptr/)
* بنية [Convert](../)
* مساحة أسماء [System](../../)
* مكتبة [Aspose.Slides](../../../)