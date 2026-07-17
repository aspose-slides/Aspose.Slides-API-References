---
title: BothArrayOrList
second_title: Aspose.Slides for C++ API 参考
description: 检查两个类型参数是否都是数组或列表。如果是，则将 value 成员设置为 true，否则设置为 false.
type: docs
weight: 131
url: /zh/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList 类型别名


检查两个类型参数是否都是数组或列表。如果是，则将 value 成员设置为 true，否则设置为 false.

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList = typedef std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```


## 另请参见

* 命名空间 [System::TestPredicates::TypeTraits](../)
* 库 [Aspose.Slides](../../)