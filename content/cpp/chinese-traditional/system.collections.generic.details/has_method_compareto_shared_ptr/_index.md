---
title: has_method_compareto_shared_ptr
second_title: Aspose.Slides for C++ API 參考文件
description: "檢查指定類型中是否存在 CompareTo(SharedPtr<T>) 方法。若存在，繼承 std::true_type，否則繼承 std::false_type。可用於 std::enable_if。"
type: docs
weight: 183
url: /zh-hant/system.collections.generic.details/has_method_compareto_shared_ptr/
---
## has_method_compareto_shared_ptr struct


檢查指定類型中是否存在 CompareTo(SharedPtr<T>) 方法。若存在，繼承 std::true_type，否則繼承 std::false_type。可用於 std::enable_if。

```cpp
template<typename T,typename Sfinae>class has_method_compareto_shared_ptr : public std::false_type
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 要檢查是否存在 Equals 方法的類型。 |
| Sfinae | 用於使 SFINAE 正常工作的形式模板參數。 |

## 另請參閱

* 命名空間 [System::Collections::Generic::Details](../)
* 函式庫 [Aspose.Slides](../../)