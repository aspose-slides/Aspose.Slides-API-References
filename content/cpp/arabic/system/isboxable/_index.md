---
title: IsBoxable
second_title: مرجع API لـ Aspose.Slides للغة C++
description: مُقَدِّر القالب الذي يتحقق مما إذا كان تغليف النوع المحدد مدعومًا.
type: docs
weight: 1665
url: /ar/system/isboxable/
---
## IsBoxable struct

مُقَدِّر القالب الذي يتحقق مما إذا كان تغليف النوع المحدد مدعومًا.

```cpp
template<typename T>class IsBoxable : public std::integral_constant<bool, std::is_base_of<Details::BoxableObjectBase, T>::value||std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع للتحقق منه |

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)