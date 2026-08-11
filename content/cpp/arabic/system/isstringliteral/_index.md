---
title: IsStringLiteral
second_title: مرجع API لـ Aspose.Slides للغة C++
description: سحر القوالب للتحقق مما إذا كان النوع حرفية سلسلة.
type: docs
weight: 1730
url: /ar/system/isstringliteral/
---
## بنية IsStringLiteral


سحر القوالب للتحقق مما إذا كان النوع عبارة عن حرفية سلسلة.

```cpp
template<typename T,typename CharT>class IsStringLiteral : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_array<T>::value>
```


### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T | النوع المفحوص. |
| CharT | نوع الحرف للتحقق منه. |

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)