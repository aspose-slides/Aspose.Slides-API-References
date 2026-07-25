---
title: Equals()
second_title: Aspose.Slides for C++ API リファレンス
description: operator==() を使用して指定された値の等価性を判断します。
type: docs
weight: 66
url: /ja/system.boxedvaluedetail/equals/
---
## System::BoxedValueDetail::Equals(T, T) 関数

指定された値の等価性を [operator==()](../../system/operator_equal_equal/) を使用して判断します。

```cpp
template<typename T> std::enable_if<detail::has_operator_equal<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| この | 比較される値の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value1 | T | 最初の比較対象 |
| value2 | T | 2 番目の比較対象 |

### 戻り値

[operator==()](../../system/operator_equal_equal/) によって判定されたとき、指定された値が等しい場合は true、そうでない場合は false

## System::BoxedValueDetail::Equals(T, T) 関数

指定された値の等価性をメソッド [System::Object::Equals()](../../system/object/equals/) を使用して判断します。

```cpp
template<typename T> std::enable_if<detail::has_only_method_equals<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| この | 比較される値の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value1 | T | 最初の比較対象 |
| value2 | T | 2 番目の比較対象 |

### 戻り値

[Equals()](./) メソッドによって判定されたとき、指定された値が等しい場合は true、そうでない場合は false

## 参照

* 名前空間 [System::BoxedValueDetail](../)
* ライブラリ [Aspose.Slides](../../)