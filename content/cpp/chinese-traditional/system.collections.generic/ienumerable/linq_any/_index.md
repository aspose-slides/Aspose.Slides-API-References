---
title: LINQ_Any()
second_title: Aspose.Slides for C++ API 參考文件
description: 判斷序列是否包含任何元素。
type: docs
weight: 157
url: /zh-hant/system.collections.generic/ienumerable/linq_any/
---
## IEnumerable::LINQ_Any() 方法

判斷序列是否包含任何元素。

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_Any()
```

### 返回值

若來源序列包含任何元素，則返回 true；否則返回 false。

## IEnumerable::LINQ_Any(std::function\<bool(T)>) 方法

判斷序列中的任何元素是否存在或符合條件。

```cpp
bool System::Collections::Generic::IEnumerable<T>::LINQ_Any(std::function<bool(T)> predicate)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | 用於測試每個元素是否符合條件的函式。 |

### 返回值

若來源序列包含任何元素，則返回 true；否則返回 false。

## 參見

* 類別 [IEnumerable](../)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)