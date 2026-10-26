---
title: IsList
second_title: Aspose.Slides for C++ API 参考
description: "检查类型是否为 System::Collections::Generic::List 的特化。如果是，则 value 成员被设为 true，否则被设为 false。"
type: docs
weight: 118
url: /zh/system.testpredicates.typetraits/islist/
---
## IsList typedef

检查类型是否为 [System::Collections::Generic::List](../../system.collections.generic/list/) 的特化。如果是，则 value 成员被设为 true，否则被设为 false。

```cpp
using System::TestPredicates::TypeTraits::IsList = typedef std::is_same<T, System::Collections::Generic::List<typename T::ValueType> >
```

## 参见

* 命名空间 [System::TestPredicates::TypeTraits](../)
* 库 [Aspose.Slides](../../)