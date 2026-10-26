---
title: operator>=()
second_title: Aspose.Slides for C++ API リファレンス
description: 常に false を返します。
type: docs
weight: 183
url: /ja/system/nullable/operator_greater_equal/
---
## Nullable::operator>=(std::nullptr_t) const メソッド


常に false を返します。

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```


### 戻り値

常に - false

## Nullable::operator>=(const T1\&) const メソッド


現在のオブジェクトが表す値が、指定されたオブジェクトが表す値以上であるかどうかを、[operator>=()](./) をこれらの値に適用して判断します。

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 現在のオブジェクトが表す値と比較する値の基になる型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | const T1\& | 現在のオブジェクトと比較するオブジェクトへの const 参照 |

### 戻り値

現在のオブジェクトが表す値が、指定されたオブジェクトが表す値以上である場合は true、そうでない場合は - false

## Nullable::operator>=(const Nullable\<T1\>\&) const メソッド


現在のオブジェクトが表す値が、指定された [Nullable](../) オブジェクトが表す値以上であるかどうかを、[operator>=()](./) をこれらの値に適用して判断します。

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | [Nullable](../) オブジェクトと比較するための基になる型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | [Nullable](../) オブジェクトと比較するための const 参照 |

### 戻り値

現在のオブジェクトが表す値が、指定された [Nullable](../) オブジェクトが表す値以上である場合は true、そうでない場合は - false

## 参照

* クラス [Nullable](../)
* 構造体 [IsNullable](../../isnullable/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)