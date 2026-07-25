---
title: operator-()
second_title: Aspose.Slides for C++ API リファレンス
description: nullable と null ポインタ値を減算します。
type: docs
weight: 222
url: /ja/system/nullable/operator_minus/
---
## Nullable::operator-(T1) const メソッド


nullable と null ポインタ値を減算します。

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 右オペランドの型。nullptr_t である必要があります。 |

### 戻り値

空の [Nullable](../) オブジェクト。

## Nullable::operator-(const T1&) const メソッド


nullable と非 nullable の値を減算します。

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator-(const T1 &other) const -> Nullable<decltype(get_Value() - other)>
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 右オペランドの型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | const T1\& | 減算する値。 |

### 戻り値

減算結果。

## Nullable::operator-(const Nullable<T1>&) const メソッド


nullable 値を減算します。

```cpp
template<typename T1> auto System::Nullable<T>::operator-(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value() - other.get_Value())>
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 右オペランドの型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | 減算する値。 |

### 戻り値

減算結果。

## 参照

* クラス [Nullable](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)