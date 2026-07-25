---
title: operator+()
second_title: Aspose.Slides for C++ API リファレンス
description: Nullable<T> クラスのデフォルト構築インスタンスを返します。
type: docs
weight: 209
url: /ja/system/nullable/operator_plus/
---
## Nullable::operator+(std::nullptr_t) const method

Nullable<T> クラスのデフォルト構築インスタンスを返します。

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Nullable::operator+(const T1\&) const method

nullable と非 nullable の値を合計します。

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator+(const T1 &other) const -> Nullable<decltype(get_Value()+other)>
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 右オペランドの型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | const T1\& | 加算する値。 |

### 戻り値

加算結果。

## Nullable::operator+(const Nullable\<T1\>\&) const method

nullable の値を合計します。

```cpp
template<typename T1> auto System::Nullable<T>::operator+(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value()+other.get_Value())>
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 右オペランドの型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 加算する値。 |

### 戻り値

加算結果。

## 参照

* クラス [Nullable](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)