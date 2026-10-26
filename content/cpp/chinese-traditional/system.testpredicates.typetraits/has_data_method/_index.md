---
title: has_data_method
second_title: Aspose.Slides for C++ API 參考文件
description: "檢查型別是否具有 data() 方法。若有，繼承 std::true_type；否則繼承 std::false_type。"
type: docs
weight: 1
url: /zh-hant/system.testpredicates.typetraits/has_data_method/
---
## has_data_method 結構

檢查型別是否具有 data() 方法。若有，繼承 std::true_type，否則繼承 std::false_type。

```cpp
template<typename T,typename Enable>class has_data_method : public std::false_type
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 要檢查的型別。 |
| Enable | SFINAE 工作所需的形式參數。 |

## 另見

* 命名空間 [System::TestPredicates::TypeTraits](../)
* 函式庫 [Aspose.Slides](../../)