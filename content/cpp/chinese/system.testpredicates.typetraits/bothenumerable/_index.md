---
title: BothEnumerable
second_title: Aspose.Slides for C++ API 参考
description: 检查两个类型参数是否为 IEnumerable。如果是，则 value 成员被设置为 true，否则被设置为 false。
type: docs
weight: 144
url: /zh/system.testpredicates.typetraits/bothenumerable/
---
## BothEnumerable 类型定义

检查两个类型参数是否为 IEnumerable。如果是，则 value 成员被设置为 true，否则被设置为 false。

```cpp
using System::TestPredicates::TypeTraits::BothEnumerable = typedef std::integral_constant<bool, IsEnumerable<T1>::value && IsEnumerable<T2>::value>
```

## 另请参见

* 命名空间 [System::TestPredicates::TypeTraits](../)
* 库 [Aspose.Slides](../../)