---
title: operator()()
second_title: Aspose.Slides for C++ API 參考文件
description: 適用於具有 operator < 的類型之比較函式。
type: docs
weight: 27
url: /zh-hant/system.collections.generic/compareradapter/operator_call/
---
## ComparerAdapter::operator()(const Q\&, const Q\&) const 方法

[Comparison](../../../system/comparison/) 適用於具有 operator < 的類型之函式。

```cpp
template<typename Q> std::enable_if<detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| Q | 被比較的類型；用於檢查類型轉換可用性之模板。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | const Q\& | 第一個要比較的值。 |
| y | const Q\& | 第二個要比較的值。 |

### 回傳值

如果 **x** 被視為小於 **y**，則回傳 True，否則回傳 false。

## ComparerAdapter::operator()(const Q\&, const Q\&) const 方法

[Comparison](../../../system/comparison/) 適用於沒有 operator < 的類型之函式。

```cpp
template<typename Q> std::enable_if<!detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| Q | 被比較的類型；用於檢查類型轉換可用性之模板。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | const Q\& | 第一個要比較的值。 |
| y | const Q\& | 第二個要比較的值。 |

### 回傳值

如果已設定比較器且 **x** 被視為小於 **y**，則回傳 True，否則回傳 false。

## 另見

* Struct [ComparerAdapter](../)
* 命名空間 [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)