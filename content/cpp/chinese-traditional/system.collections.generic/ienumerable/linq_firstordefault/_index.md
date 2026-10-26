---
title: LINQ_FirstOrDefault()
second_title: Aspose.Slides for C++ API 參考
description: 傳回序列的第一個元素；如果序列為空，則傳回預設值。
type: docs
weight: 66
url: /zh-hant/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() 方法


傳回序列的第一個元素；如果序列為空，則傳回預設值。

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```


### 傳回值

序列中的第一個元素，或如果序列為空則為預設建構值。

## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) 方法


傳回符合條件的序列第一個元素；如果未找到此類元素，則傳回預設值。

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | 測試每個元素是否符合條件的函式。 |

### 傳回值

如果 source 為空或沒有元素通過 predicate 指定的測試，則為 default(T)；否則，返回 source 中第一個通過 predicate 指定測試的元素。

## 另請參閱

* 類別 [IEnumerable](../)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)