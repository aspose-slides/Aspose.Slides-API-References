---
title: operator!=()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表す値が null でないかどうかを判定します。
type: docs
weight: 144
url: /ja/system/nullable/operator_not_equal/
---
## Nullable::operator!=(std::nullptr_t) const メソッド


現在のオブジェクトが表す値が null でないかどうかを判定します。

```cpp
bool System::Nullable<T>::operator!=(std::nullptr_t) const
```


### 戻り値

現在のオブジェクトが表す値が null でない場合は true、それ以外の場合は false

## Nullable::operator!=(const T1\&) const メソッド


現在のオブジェクトが表す値が指定された値と等しくないかどうかを判定します。

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator!=(const T1 &other) const
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T1 | 比較対象となる値の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | const T1\& | 比較対象となる値への const 参照 |

### 戻り値

現在のオブジェクトが表す値が指定された値と等しくない場合は true、それ以外の場合は false

## Nullable::operator!=(const Nullable\<T1\>\&) const メソッド


現在のオブジェクトが表す値が、指定された [Nullable](../) オブジェクトが表す値と等しくないかどうかを判定します。

```cpp
template<typename T1> bool System::Nullable<T>::operator!=(const Nullable<T1> &other) const
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T1 | 比較対象となる [Nullable](../) オブジェクトの基になる型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 比較対象となる [Nullable](../) オブジェクトへの const 参照 |

### 戻り値

現在のオブジェクトが表す値が、指定された [Nullable](../) オブジェクトが表す値と等しくない場合は true、それ以外の場合は false

## 関連項目

* クラス [Nullable](../)
* 構造体 [IsNullable](../../isnullable/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)