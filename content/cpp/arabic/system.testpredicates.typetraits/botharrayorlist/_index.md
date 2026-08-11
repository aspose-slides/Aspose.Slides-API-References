---
title: BothArrayOrList
second_title: Aspose.Slides للـ C++ مرجع API
description: يتحقق مما إذا كانت كلتا معلمات النوع مصفوفات أو قوائم. إذا كان الأمر كذلك، يتم تعيين عضو value إلى true، وإلا يتم تعيينه إلى false.
type: docs
weight: 131
url: /ar/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef

يتحقق مما إذا كان كل من معلمات النوع عبارة عن مصفوفات أو قوائم. إذا كان الأمر كذلك، يتم تعيين عضو value إلى true، وإلا يتم تعيينه إلى false.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList = typedef std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```

## انظر أيضًا

* النطاق [System::TestPredicates::TypeTraits](../)
* المكتبة [Aspose.Slides](../../)