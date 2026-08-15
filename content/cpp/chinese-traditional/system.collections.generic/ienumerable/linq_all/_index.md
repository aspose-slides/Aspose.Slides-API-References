---
title: LINQ_All()
second_title: Aspose.Slides C++ API 參考
description: 判斷序列中的所有元素是否符合條件。
type: docs
weight: 144
url: /zh-hant/system.collections.generic/ienumerable/linq_all/
---
## IEnumerable::LINQ_All(std::function\<bool(T)>) 方法


判斷序列中的所有元素是否符合條件。

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_All(std::function<bool(T)> predicate)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | 用於測試每個元素是否符合條件的函式。 |

### 傳回值

如果來源序列的每個元素皆通過指定 predicate 的測試，或序列為空，則回傳 true；否則回傳 false。

## 另見

* 類別 [IEnumerable](../)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)