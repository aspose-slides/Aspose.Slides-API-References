---
title: Nullable
second_title: Aspose.Slides for C++ API リファレンス
description: 前方宣言。
type: docs
weight: 1106
url: /ja/system/nullable/
---
## Nullable クラス

Forward declaration.

```cpp
template<typename T>class Nullable
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | [Nullable](./) クラスによって拡張される基礎値型 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| std::enable_if\<[IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [Equals](./equals/)(const T1\&) const | 現在のオブジェクトが表す値が、指定された [Nullable](./) オブジェクトが表す値と等しいかどうかを判断します。 |
| **bool** [get_HasValue](./get_hasvalue/)() const | 現在のオブジェクトが任意の値を表すかどうかを判断します。 |
| T [get_Value](./get_value/)() const | 現在のオブジェクトが表す値のコピーを返します。 |
| int [GetHashCode](./gethashcode/)() const | 現在のオブジェクトのハッシュコードを返します。 |
| T [GetValueOrDefault](./getvalueordefault/)(T) | 現在のオブジェクトが表す値、または現在のオブジェクトがnullの場合は指定された値を返します。 |
| T [GetValueOrDefault](./getvalueordefault/)() |  |
| **bool** [IsNull](./isnull/)() const | 現在のオブジェクトがnull値を表すかどうかを判断します。 |
| [Nullable](./nullable/)() | null値を表すインスタンスを構築します。 |
| [Nullable](./nullable/)(std::nullptr_t) | nullを表すインスタンスを構築します。 |
| [Nullable](./nullable/)(const T1\&) | [Nullable](./) クラスのインスタンスを構築し、指定された値を基礎型Tの値に変換（必要な場合）して表します。 |
| [Nullable](./nullable/)(const [Nullable](./)\<T1\>\&) | 指定された [Nullable](./) オブジェクトが表す値を表すインスタンスを構築します。指定された nullable オブジェクトが構築されたインスタンスの基礎型と異なる型の値を表す場合、表された値は型 T に変換されます。 |
| **bool** [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<**bool**()>\&, **bool**) const | このオブジェクトと **other** の両方がnullでないかを確認し、そうであればラムダを呼び出すヘルパー関数です。実装で使用されます。 |
| [operator const T &](./operator_const_t__and/)() const | 現在のオブジェクトが表す値への const 参照を返します。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 現在のオブジェクトが表す値がnullでないかどうかを判断します。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&) const | 現在のオブジェクトが表す値が、指定された値と等しくないかどうかを判断します。 |
| **bool** [operator!=](./operator_not_equal/)(const [Nullable](./)\<T1\>\&) const | 現在のオブジェクトが表す値が、指定された [Nullable](./) オブジェクトが表す値と等しくないかどうかを判断します。 |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator&=](./operator_and_equal/)(**bool**) | 指定された値を右側引数として、現在のオブジェクトが表す値に [operator&=()](./operator_and_equal/) を適用します。 |
| [Nullable](./)\<T\> [operator+](./operator_plus/)(std::nullptr_t) const | Nullable<T> クラスのデフォルト構築されたインスタンスを返します。 |
| auto [operator+](./operator_plus/)(const T1\&) const | nullable と non-nullable の値を合計します。 |
| auto [operator+](./operator_plus/)(const [Nullable](./)\<T1\>\&) const | nullable の値を合計します。 |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(std::nullptr_t) | 現在のオブジェクトをリセットし、null値を表すようにします。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator+=](./operator_plus_equal/)(const T1\&) | 指定された値を右側引数として、現在のオブジェクトが表す値に [operator+=()](./operator_plus_equal/) を適用します。 |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(const [Nullable](./)\<T1\>\&) | 指定された [Nullable](./) オブジェクトが表す値を右側引数として、現在のオブジェクトが表す値に [operator+=()](./operator_plus_equal/) を適用します。 |
| [Nullable](./)\<T\> [operator-](./operator_minus/)(T1) const | nullable と null ポインタ値を減算します。 |
| auto [operator-](./operator_minus/)(const T1\&) const | nullable と non-nullable の値を減算します。 |
| auto [operator-](./operator_minus/)(const [Nullable](./)\<T1\>\&) const | nullable の値を減算します。 |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(T1) | null値を表す [Nullable](./) クラスのインスタンスを返します。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator-=](./operator_minus_equal/)(const T1\&) | 指定された値を右側引数として、現在のオブジェクトが表す値に [operator-=()](./operator_minus_equal/) を適用します。 |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(const [Nullable](./)\<T1\>\&) | 指定された [Nullable](./) オブジェクトが表す値を右側引数として、現在のオブジェクトが表す値に [operator-=()](./operator_minus_equal/) を適用します。 |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const | 常に false を返します。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&) const | 現在のオブジェクトが表す値と指定された値に [operator<()](./operator_less/) を適用し、前者が後者より小さいかどうかを判断します。 |
| **bool** [operator<](./operator_less/)(const [Nullable](./)\<T1\>\&) const | 現在のオブジェクトが表す値と指定された [Nullable](./) オブジェクトが表す値に [operator<()](./operator_less/) を適用し、前者が後者より小さいかどうかを判断します。 |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const | 常に false を返します。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&) const | 現在のオブジェクトが表す値と指定された値に [operator<=()](./operator_less_equal/) を適用し、前者が後者以下かどうかを判断します。 |
| **bool** [operator<=](./operator_less_equal/)(const [Nullable](./)\<T1\>\&) const | 現在のオブジェクトが表す値と指定された [Nullable](./) オブジェクトが表す値に [operator<=()](./operator_less_equal/) を適用し、前者が後者以下かどうかを判断します。 |
| [Nullable](./)\<T\> [operator=](./operator_equal/)(std::nullptr_t) | 現在のオブジェクトに null を代入します。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value\&&\!std::is_null_pointer\<T1\>::value, [Nullable](./)\<T\>\&\>::type [operator=](./operator_equal/)(const T1\&) | オブジェクトが現在表す値を、指定された値に置き換えます。 |
| [Nullable](./)\<T\>\& [operator=](./operator_equal/)(const [Nullable](./)\<T1\>\&) | オブジェクトが現在表す値を、指定された値に置き換えます。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 現在のオブジェクトが表す値が null かどうかを判断します。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&) const | 現在のオブジェクトが表す値が、指定された値と等しいかどうかを判断します。 |
| **bool** [operator==](./operator_equal_equal/)(const [Nullable](./)\<T1\>\&) const | 現在のオブジェクトが表す値が、指定された [Nullable](./) オブジェクトが表す値と等しいかどうかを判断します。 |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const | 常に false を返します。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&) const | 現在のオブジェクトが表す値と指定された値に [operator>()](./operator_greater/) を適用し、前者が後者より大きいかどうかを判断します。 |
| **bool** [operator>](./operator_greater/)(const [Nullable](./)\<T1\>\&) const | 現在のオブジェクトが表す値と指定された [Nullable](./) オブジェクトが表す値に [operator>()](./operator_greater/) を適用し、前者が後者より大きいかどうかを判断します。 |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const | 常に false を返します。 |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&) const | 現在のオブジェクトが表す値と指定されたオブジェクトに [operator>=()](./operator_greater_equal/) を適用し、前者が後者以上かどうかを判断します。 |
| **bool** [operator>=](./operator_greater_equal/)(const [Nullable](./)\<T1\>\&) const | 現在のオブジェクトが表す値と指定された [Nullable](./) オブジェクトが表す値に [operator>=()](./operator_greater_equal/) を適用し、前者が後者以上かどうかを判断します。 |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator|=](./operator_or_equal/)(**bool**) | 指定された値を右側引数として、現在のオブジェクトが表す値に [operator|=()](./operator_or_equal/) を適用します。 |
| void [reset](./reset/)() | 現在表されている値を null に設定します。 |
| void [set_Value](./set_value/)(const T\&) | nullable オブジェクトに新しい値を設定します。 |
| [String](../string/) [ToString](./tostring/)() const | 現在のオブジェクトが表す値を文字列に変換します。 |

## 型エイリアス

| 型エイリアス | 説明 |
| --- | --- |
| [ValueType](./valuetype/) | このクラスが表す値の型のエイリアスです。 |

## 備考

指定された型の値を表し、null を代入できます。この型はスタック上に割り当て、値または参照で関数に渡すべきです。[System::SmartPtr](../smartptr/) クラスをこの型のオブジェクト管理に使用しないでください。

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)