---
title: IsStringPointer
second_title: مرجع API لـ Aspose.Slides للغة C++
description: سحر القالب للتحقق مما إذا كان النوع مؤشراً إلى سلسلة أحرف.
type: docs
weight: 1743
url: /ar/system/isstringpointer/
---
## IsStringPointer struct

سحر القالب للتحقق مما إذا كان النوع مؤشراً إلى سلسلة أحرف.

```cpp
template<typename T,typename CharT>class IsStringPointer : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_pointer<T>::value>
```

### معلمات القالب

| معمل | الوصف |
| --- | --- |
| T | النوع المفحص. |
| CharT | نوع الأحرف للتحقق منه. |

## انظر أيضاً

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)