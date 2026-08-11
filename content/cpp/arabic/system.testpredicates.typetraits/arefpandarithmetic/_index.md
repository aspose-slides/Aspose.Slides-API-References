---
title: AreFPandArithmetic
second_title: مرجع API Aspose.Slides للـ C++
description: يتحقق مما إذا كان T1 عددًا حسابيًا و T2 عددًا عائمًا، أو العكس. إذا كان الأمر كذلك، يضبط عضو القيمة إلى true، وإلا يكون false.
type: docs
weight: 79
url: /ar/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef

يتحقق مما إذا كان **T1** عددًا حسابيًا و **T2** عددًا عائمًا، أو العكس. إذا كان الأمر كذلك، يضبط عضو القيمة إلى true، وإلا يكون false.

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic = typedef std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```


## انظر أيضًا

* نطاق [System::TestPredicates::TypeTraits](../)
* مكتبة [Aspose.Slides](../../)