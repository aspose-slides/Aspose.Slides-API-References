---
title: NullableBoolHelper()
second_title: Aspose.Slides للغة C++ مرجع API
description: دالة مساعدة للتحقق مما إذا كان كل من this و other غير فارغين واستدعاء لامبدا إذا كان ذلك كذلك. يُستخدم في implementation.s.
type: docs
weight: 105
url: /ar/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper(const T1\&, const std::function\<bool()>\&, bool) const طريقة


دالة مساعد للتحقق مما إذا كان **this** و **other** كلاهما غير فارغين واستدعاء لامبدا إذا كان ذلك كذلك. يُستخدم في implementation.s.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T1 | نوع nullable آخر. |

### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| other | const T1\& | قيمة nullable أخرى للمقارنة معها. |
| f | const std::function\<**bool**()>\& | لامبدا لاستدعائه إذا كان كل من **this** و **other** غير فارغين. |
| default_if_both_are_null | **bool** | قيمة الإرجاع إذا كانت القيمتين فارغتين. |

### قيمة الإرجاع

false إذا كان أي من **this** أو **other** فارغًا؛ **default_if_both_are_null** إذا كان كلاهما فارغًا؛ نتيجة استدعاء **f** إذا كان كلاهما غير فارغ.

## انظر أيضًا

* فئة [Nullable](../)
* نطاق الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)