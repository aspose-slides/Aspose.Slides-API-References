---
title: operator+=()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトをリセットし、null 値を表すようにします。
type: docs
weight: 235
url: /ja/system/nullable/operator_plus_equal/
---
## Nullable::operator+=(std::nullptr_t) メソッド


現在のオブジェクトをリセットし、null 値を表すようにします。

```cpp
Nullable<T> System::Nullable<T>::operator+=(std::nullptr_t)
```


### Return Value

self のコピー

## Nullable::operator+=(const T1\&) メソッド


[operator+=()](./) を、右側引数として指定された値を使用して、現在のオブジェクトが表す値に適用します。

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator+=(const T1 &other)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | [operator+=()](./) の右側値として使用される値の型 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | 現在のオブジェクトが表す値に適用される [operator+=()](./) の右側値として使用される値への定数参照です。 |

### Return Value

self への参照

## Nullable::operator+=(const Nullable\<T1\>\&) メソッド


[operator+=()](./) を、指定された [Nullable](../) オブジェクトが表す値を右側引数として、現在のオブジェクトが表す値に適用します。

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator+=(const Nullable<T1> &other)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | [operator+=()](./) の右側引数として使用される値を表す [Nullable](../) オブジェクトの基礎型 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 現在のオブジェクトが表す値に適用される [operator+=()](./) の右側引数として使用される [Nullable](../) オブジェクトの値への定数参照です。 |

### Return Value

self への参照

## See Also

* クラス [Nullable](../)
* 構造体 [IsNullable](../../isnullable/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)