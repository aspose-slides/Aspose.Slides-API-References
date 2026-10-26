---
title: has_method_compareto
second_title: Aspose.Slides for C++ API 參考
description: "檢查指定類型中是否存在 CompareTo 方法。若存在，繼承 std::true_type，否則繼承 std::false_type。可用於 std::enable_if."
type: docs
weight: 170
url: /zh-hant/system.collections.generic.details/has_method_compareto/
---
## has_method_compareto struct

檢查指定類型中是否存在 CompareTo 方法。若存在，繼承 std::true_type；否則繼承 std::false_type。可用於 std::enable_if.

```cpp
template<typename T,typename Sfinae>class has_method_compareto : public std::false_type
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 要檢查是否存在 Equals 方法的類型。 |
| Sfinae | 用於使 SFINAE 起作用的形式模板參數。 |

## 參見

* 命名空間 [System::Collections::Generic::Details](../)
* 函式庫 [Aspose.Slides](../../)