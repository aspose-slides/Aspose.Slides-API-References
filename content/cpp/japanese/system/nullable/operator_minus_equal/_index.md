---
title: operator-=()
second_title: Aspose.Slides for C++ API リファレンス
description: null 値を表す Nullable クラスのインスタンスを返します。
type: docs
weight: 248
url: /ja/system/nullable/operator_minus_equal/
---
## Nullable::operator-=(T1) メソッド

[Nullable](../) クラスのインスタンスを返します。null 値を表します。

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-=(T1)
```

## Nullable::operator-=(const T1\&) メソッド

指定された値を右側引数として使用し、現在のオブジェクトが表す値に [operator-=()](./) を適用します。

```cpp
template<typename T1,typename> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator-=(const T1 &other)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T1 | [operator-=()](./) の右側値として使用される値の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | const T1\& | 現在のオブジェクトが表す値に適用される [operator-=()](./) の右側値として使用される値への定数参照 |

### 戻り値

自身への参照

## Nullable::operator-=(const Nullable\<T1\>\&) メソッド

指定された [Nullable](../) オブジェクトが表す値を右側引数として使用し、現在のオブジェクトが表す値に [operator-=()](./) を適用します。

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator-=(const Nullable<T1> &other)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T1 | [Nullable](../) オブジェクトの基になる型で、そのオブジェクトが表す値は [operator-=()](./) の右側引数として使用されます |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 現在のオブジェクトが表す値に適用される [operator-=()](./) の右側引数として使用される [Nullable](../) オブジェクトの値への定数参照 |

### 戻り値

自身への参照

## 参照

* クラス [Nullable](../)
* 構造体 [IsNullable](../../isnullable/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)