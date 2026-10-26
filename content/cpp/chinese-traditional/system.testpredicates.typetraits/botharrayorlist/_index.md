---
title: BothArrayOrList
second_title: Aspose.Slides for C++ API 參考
description: 檢查兩個型別參數是否皆為陣列或列表。若是，value 成員設定為 true，否則設定為 false。
type: docs
weight: 131
url: /zh-hant/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList typedef


檢查兩個型別參數是否皆為陣列或列表。若是，value 成員設定為 true，否則設定為 false。

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList = typedef std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```


## 另請參閱

* 命名空間 [System::TestPredicates::TypeTraits](../)
* 函式庫 [Aspose.Slides](../../)