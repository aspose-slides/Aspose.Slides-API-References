---
title: LINQ_GroupBy()
second_title: Aspose.Slides for C++ API 參考文件
description: 將序列中的元素分組。
type: docs
weight: 287
url: /zh-hant/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) 方法


將序列中的元素分組。

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| Key | keyPredicate 回傳之鍵的型別 |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | 用於為每個元素擷取鍵的函式。 |

### 傳回值

包含物件序列和鍵的 [IEnumerable](../)


## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) 方法


將序列中的元素分組。

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| Key | keyPredicate 回傳之鍵的型別 |
| Element | elementSelector 回傳之元素的型別 |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | 用於為每個元素擷取鍵的函式。 |
| elementSelector | [System::Func](../../../system/func/)\<T, Element\> | 用於為每個元素擷取值鍵的函式。 |

### 傳回值

包含物件序列和鍵的 [IEnumerable](../)


## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) 方法




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) 方法




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## 參見

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IEnumerable](../)
* 類別 [IGrouping](../../../system.linq/igrouping/)
* 類別 [Func](../../../system/func/)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)