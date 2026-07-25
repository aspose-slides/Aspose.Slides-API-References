---
title: operator<()
second_title: Aspose.Slides for C++ API リファレンス
description: 常に false を返します。
type: docs
weight: 170
url: /ja/system/nullable/operator_less/
---
## Nullable::operator<(std::nullptr_t) const メソッド

常に false を返します。

```cpp
bool System::Nullable<T>::operator<(std::nullptr_t) const
```

## Nullable::operator<(const T1\&) const メソッド

現在のオブジェクトが表す値が、[operator<()](./) をこれらの値に適用して、指定された値より小さいかどうかを判断します。

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<(const T1 &other) const
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T1 | 比較対象の値の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | const T1\& | 比較対象の値への定数参照 |

### 戻り値

現在のオブジェクトが表す値が指定された値より小さい場合は true、そうでない場合は false

## Nullable::operator<(const Nullable\<T1\>\&) const メソッド

現在のオブジェクトが表す値が、[operator<()](./) をこれらの値に適用して、指定された [Nullable](../) オブジェクトが表す値より小さいかどうかを判断します。

```cpp
template<typename T1> bool System::Nullable<T>::operator<(const Nullable<T1> &other) const
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T1 | [Nullable](../) オブジェクトを比較するための基になる型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 比較対象の [Nullable](../) オブジェクトへの定数参照 |

### 戻り値

現在のオブジェクトが表す値が、指定された [Nullable](../) オブジェクトが表す値より小さい場合は true、そうでない場合は false

## 参照

* クラス [Nullable](../)
* 構造体 [IsNullable](../../isnullable/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)