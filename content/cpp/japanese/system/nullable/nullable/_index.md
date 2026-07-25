---
title: Nullable()
second_title: Aspose.Slides for C++ API リファレンス
description: null 値を表すインスタンスを構築します。
type: docs
weight: 1
url: /ja/system/nullable/nullable/
---
## Nullable::Nullable() コンストラクタ

null 値を表すインスタンスを構築します。

```cpp
System::Nullable<T>::Nullable()
```

## Nullable::Nullable(std::nullptr_t) コンストラクタ

null を表すインスタンスを構築します。

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```

## Nullable::Nullable(const T1\&) コンストラクタ

[Nullable](../) クラスのインスタンスを構築します。このインスタンスは、必要に応じて基底型 T の値に変換された指定された値を表します。

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 指定された値の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const T1\& | 新しく構築された [Nullable](../) オブジェクトが表す値への定数参照 |

## Nullable::Nullable(const Nullable\<T1\>\&) コンストラクタ

指定された [Nullable](../) オブジェクトが表す値を表すインスタンスを構築します。指定された nullable オブジェクトは、構築されたインスタンスの基底型とは異なる型の値を表す場合があり、その場合は表される値が型 T に変換されます。

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 指定された [Nullable](../) オブジェクトが表す値の型 |

## 参照

* クラス [Nullable](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)