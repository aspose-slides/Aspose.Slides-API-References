---
title: AreFPandArithmetic
second_title: Aspose.Slides for C++ API 参考
description: 检查 T1 是否为算术类型且 T2 为浮点类型，或反之。如果是，则将 value 成员设为 true，否则为 false。
type: docs
weight: 79
url: /zh/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic typedef

检查 **T1** 是否为算术类型且 **T2** 为浮点类型，或反之。如果是，则将 value 成员设为 true，否则为 false。

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic = typedef std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```

## 另见

* 命名空间 [System::TestPredicates::TypeTraits](../)
* 库 [Aspose.Slides](../../)