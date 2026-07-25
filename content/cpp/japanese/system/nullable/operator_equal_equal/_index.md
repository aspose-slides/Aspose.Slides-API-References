---
title: operator==()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表す値が null かどうかを判定します。
type: docs
weight: 118
url: /ja/system/nullable/operator_equal_equal/
---
## Nullable::operator==(std::nullptr_t) const メソッド


現在のオブジェクトが表す値が null かどうかを判定します。

```cpp
bool System::Nullable<T>::operator==(std::nullptr_t) const
```


### 戻り値

True if the value represented by the current object is null, otherwise - false

## Nullable::operator==(const T1\&) const メソッド


現在のオブジェクトが表す値が指定された値と等しいかどうかを判定します。

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator==(const T1 &other) const
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 比較対象となる値の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | const T1\& | 比較対象となる値への定数参照 |

### 戻り値

True if the value represented by the current object is equal to the specified value, otherwise - false

## Nullable::operator==(const Nullable\<T1\>\&) const メソッド


現在のオブジェクトが表す値が、指定された [Nullable](../) オブジェクトが表す値と等しいかどうかを判定します。

```cpp
template<typename T1> bool System::Nullable<T>::operator==(const Nullable<T1> &other) const
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 比較対象となる [Nullable](../) オブジェクトの基底型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 比較対象となる [Nullable](../) オブジェクトへの定数参照 |

### 戻り値

True if the value represented by the current object is equal to the value represented by the specified [Nullable](../) object, otherwise - false

## 関連項目

* クラス [Nullable](../)
* 構造体 [IsNullable](../../isnullable/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)