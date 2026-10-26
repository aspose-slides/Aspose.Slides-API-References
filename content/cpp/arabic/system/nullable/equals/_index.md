---
title: Equals()
second_title: مرجع API Aspose.Slides للـ C++
description: يحدد ما إذا كانت القيمة التي يمثلها الكائن الحالي مساوية للقيمة التي يمثلها الكائن Nullable المحدد.
type: docs
weight: 131
url: /ar/system/nullable/equals/
---
## Nullable::Equals(const T1\&) const طريقة

يحدد ما إذا كانت القيمة التي يمثلها الكائن الحالي مساوية للقيمة التي يمثلها الكائن [Nullable](../) المحدد.

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | النوع الأساسي للكائن [Nullable](../) للمقارنة به |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| other | const T1\& | إشارة ثابتة إلى الكائن [Nullable](../) للمقارنة به |

### قيمة الإرجاع

صحيح إذا كانت القيمة التي يمثلها الكائن الحالي مساوية للقيمة التي يمثلها الكائن [Nullable](../) المحدد، وإلا - خطأ

## انظر أيضاً

* الفئة [Nullable](../)
* البنية [IsNullable](../../isnullable/)
* المجال [System](../../)
* المكتبة [Aspose.Slides](../../../)