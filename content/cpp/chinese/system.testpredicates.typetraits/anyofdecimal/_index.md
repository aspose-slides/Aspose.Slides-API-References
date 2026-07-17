---
title: AnyOfDecimal
second_title: Aspose.Slides for C++ API 参考
description: "检查至少一个类型参数是 System::Decimal。如果是，则将 value 成员设为 true，否则为 false。"
type: docs
weight: 92
url: /zh/system.testpredicates.typetraits/anyofdecimal/
---
## AnyOfDecimal typedef

检查至少一个类型参数是 [System::Decimal](../../system/decimal/)。如果是，则将 value 成员设为 true，否则为 false。

```cpp
using System::TestPredicates::TypeTraits::AnyOfDecimal = typedef std::integral_constant<bool, std::is_same<T1, System::Decimal>::value || std::is_same<T2, System::Decimal>::value>
```

## 另请参见

* 命名空间 [System::TestPredicates::TypeTraits](../)
* 库 [Aspose.Slides](../../)