---
title: operator=()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトに null を割り当てます。
type: docs
weight: 14
url: /ja/system/nullable/operator_equal/
---
## Nullable::operator=(std::nullptr_t) メソッド


現在のオブジェクトに null を割り当てます。

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```


### 戻り値

[Nullable](../) オブジェクトは null 値を表します。

## Nullable::operator=(const T1\&) メソッド


オブジェクトが現在表している値を指定されたものに置き換えます。

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```


### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| The | 現在のオブジェクトが表す新しい値の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | const T1\& | 現在のオブジェクトが表す新しい値 |

### 戻り値

自身への参照

## Nullable::operator=(const Nullable\<T1\>\&) メソッド


オブジェクトが現在表している値を指定されたものに置き換えます。

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```


### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| The | 現在のオブジェクトが表す新しい値の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | const [Nullable](../)\<T1\>\& | 現在のオブジェクトが表す新しい値 |

### 戻り値

自身への参照

## 参照

* クラス [Nullable](../)
* 構造体 [IsNullable](../../isnullable/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)