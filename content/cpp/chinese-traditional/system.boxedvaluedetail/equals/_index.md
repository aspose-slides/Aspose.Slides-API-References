---
title: Equals()
second_title: Aspose.Slides for C++ API 參考文件
description: 使用 operator==() 判定指定值的相等性。
type: docs
weight: 66
url: /zh-hant/system.boxedvaluedetail/equals/
---
## System::BoxedValueDetail::Equals(T, T) 函式

使用 [operator==()](../../system/operator_equal_equal/) 判定指定值的相等性。

```cpp
template<typename T> std::enable_if<detail::has_operator_equal<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| 類型 | 比較值的型別 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value1 | T | 第一個比較項 |
| value2 | T | 第二個比較項 |

### 返回值

如果指定的值由 [operator==()](../../system/operator_equal_equal/) 判定相等，則返回 True，否則返回 false

## System::BoxedValueDetail::Equals(T, T) 函式

使用方法 [System::Object::Equals()](../../system/object/equals/) 判定指定值的相等性。

```cpp
template<typename T> std::enable_if<detail::has_only_method_equals<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| 類型 | 比較值的型別 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value1 | T | 第一個比較項 |
| value2 | T | 第二個比較項 |

### 返回值

如果指定的值由方法 [Equals()](./) 判定相等，則返回 True，否則返回 false

## 參見

* 命名空間 [System::BoxedValueDetail](../)
* 函式庫 [Aspose.Slides](../../)