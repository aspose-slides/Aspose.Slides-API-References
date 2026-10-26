---
title: operator!=()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: عامل مقارنة عدم المساواة.
type: docs
weight: 313
url: /ar/system/string/operator_not_equal/
---
## String::operator!=(const String\&) const الطريقة

عامل عدم المساواة.

```cpp
bool System::String::operator!=(const String &str) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) للمقارنة الحالية بـ. |

### قيمة الإرجاع

false إذا كانت السلسلتان فارغتين أو كلاهما غير فارغ وتطابقان، true بخلاف ذلك.

## String::operator!=(std::nullptr_t) const الطريقة

يتحقق مما إذا كانت السلسلة غير فارغة. يطبق نفس المنطق كالنداء [IsNull()](../isnull/).

```cpp
bool System::String::operator!=(std::nullptr_t) const
```

### قيمة الإرجاع

false إذا كانت السلسلة فارغة، true بخلاف ذلك.

## أنظر أيضًا

* الصنف [String](../)
* المجال [System](../../)
* المكتبة [Aspose.Slides](../../../)