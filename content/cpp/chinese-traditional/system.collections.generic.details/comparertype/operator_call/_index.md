---
title: operator()()
second_title: Aspose.Slides for C++ API 參考文件
description: 比較實作 IComparable 介面的值類型。
type: docs
weight: 1
url: /zh-hant/system.collections.generic.details/comparertype/operator_call/
---
## ComparerType::operator()(const Q\&, const Q\&) const method

比較實作 [IComparable](../../../system/icomparable/) 介面的值類型。

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<Q>, Q>::value||has_method_compareto<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| Q | 要比較的類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| a | const Q\& | 左側值。 |
| b | const Q\& | 右側值。 |

### 返回值

如果 **a** 被視為小於 **b**，則返回 true，否則返回 false。

## ComparerType::operator()(const Q\&, const Q\&) const method

比較原始值類型以及未實作 [IComparable](../../../system/icomparable/) 介面的物件。

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<IComparable<Q>, Q>::value||has_method_compareto<Q>::value)&&!std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| Q | 要比較的類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| a | const Q\& | 左側值。 |
| b | const Q\& | 右側值。 |

### 返回值

如果 **a** 被視為小於 **b**，則返回 true，否則返回 false。

## ComparerType::operator()(const Q\&, const Q\&) const method

比較浮點數類型。

```cpp
template<typename Q> std::enable_if<std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| Q | 要比較的類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| a | const Q\& | 左側值。 |
| b | const Q\& | 右側值。 |

### 返回值

如果 **a** 被視為小於 **b**，則返回 true，否則返回 false。

## 另請參閱

* 類別 [IComparable](../../../system/icomparable/)
* 結構 [has_method_compareto](../../has_method_compareto/)
* 結構 [ComparerType](../)
* 命名空間 [System::Collections::Generic::Details](../../)
* 函式庫 [Aspose.Slides](../../../)