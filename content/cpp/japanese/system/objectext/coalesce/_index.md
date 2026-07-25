---
title: Coalesce()
second_title: Aspose.Slides for C++ API リファレンス
description: null 許容でない型に対する '??' 演算子の実装です。
type: docs
weight: 170
url: /ja/system/objectext/coalesce/
---
## ObjectExt::Coalesce(T0, T1) メソッド


non-nullable 型に対する '??' 演算子の実装です。

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T0 | LHS の値の型。 |
| T1 | RHS 式をカプセル化するラムダの型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | T0 | LHS の値。 |
| func | T1 | RHS 式。 |

### 戻り値

LHS の値が null でない場合は LHS を返し、そうでない場合は RHS 式を計算して結果を返します。

## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) メソッド


nullable 型に対する '??' 演算子の実装です。

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T0 | LHS の値の型。 |
| T1 | RHS 式をカプセル化するラムダの型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [System::Nullable](../../nullable/)\<T0\> | LHS の値。 |
| func | T1 | RHS 式。 |

### 戻り値

LHS の値が null でない場合は LHS を返し、そうでない場合は RHS 式を計算して結果を返します。

## 参照

* クラス [ObjectExt](../)
* クラス [Nullable](../../nullable/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)