---
title: IsStringByteSequence
second_title: مرجع API لـ Aspose.Slides للغة C++
description: سحر القالب للتحقق مما إذا كان النوع تسلسلًا من أحرف السلسلة.
type: docs
weight: 1717
url: /ar/system/isstringbytesequence/
---
## IsStringByteSequence بنية

سحر القالب للتحقق مما إذا كان النوع تسلسلًا من أحرف السلسلة.

```cpp
template<typename T,typename CharT>class IsStringByteSequence : public std::integral_constant<bool, std::is_same<std::remove_const<std::remove_pointer<std::decay<T>::type>::type>::type, CharT>::value>
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع يتم فحصه. |
| CharT | نوع الحرف للتحقق منه. |

## انظر أيضًا

* نطاق [System](../)
* مكتبة [Aspose.Slides](../../)