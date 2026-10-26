---
title: has_print_to_method
second_title: Aspose.Slides C++ API 參考
description: "檢查 PrintTo 函式是否有接受給定型別作為第一個參數的重載。若存在重載，繼承 std::true_type，否則繼承 std::false_type。"
type: docs
weight: 27
url: /zh-hant/system.testpredicates.typetraits/has_print_to_method/
---
## has_print_to_method struct


檢查 PrintTo 函式是否有接受給定型別作為第一個參數的重載。若存在重載，繼承 std::true_type，否則繼承 std::false_type。

```cpp
template<typename T,typename Enable>class has_print_to_method : public std::false_type
```


### 模板參數

| Parameter | Description |
| --- | --- |
| T | 要檢查的型別。 |
| Enable | 用於讓 SFINAE 工作的形式參數。 |

## 參見

* 命名空間 [System::TestPredicates::TypeTraits](../)
* 函式庫 [Aspose.Slides](../../)