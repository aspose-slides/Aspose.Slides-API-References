---
title: AnyOfDecimal
second_title: Aspose.Slides C++ API 參考
description: "檢查是否至少有一個類型參數是 System::Decimal。如果是，將 value 成員設為 true，否則為 false。"
type: docs
weight: 92
url: /zh-hant/system.testpredicates.typetraits/anyofdecimal/
---
## AnyOfDecimal typedef


檢查是否至少有一個類型參數是 [System::Decimal](../../system/decimal/)。如果是，將 value 成員設為 true，否則為 false。

```cpp
using System::TestPredicates::TypeTraits::AnyOfDecimal = typedef std::integral_constant<bool, std::is_same<T1, System::Decimal>::value || std::is_same<T2, System::Decimal>::value>
```


## 參見

* 命名空間 [System::TestPredicates::TypeTraits](../)
* 函式庫 [Aspose.Slides](../../)