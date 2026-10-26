---
title: Enum
second_title: Aspose.Slides for C++ API リファレンス
description: enum 型の値に対していくつかの操作を行うメソッドを提供します。これはインスタンスを持たない静的型です。いかなる手段でもインスタンスを作成してはなりません。
type: docs
weight: 1587
url: /ja/system/enum/
---
## 列挙体構造体

列挙型の値に対していくつかの操作を行うメソッドを提供します。これはインスタンスサービスを持たない静的型です。いかなる手段でもインスタンスを作成してはなりません。

```cpp
template<class E,class Guard>class Enum
```

### テンプレートパラメーター

| パラメータ | 説明 |
| --- | --- |
| E | クラスが扱う列挙値の列挙型 |
| Guard | サービス型引数で、**E** が列挙可能型であることを保証することが目的です |

## メソッド

| メソッド | 説明 |
| --- | --- |
| static int [Compare](./compare/)(E, T) | 指定された列挙定数の値の算術比較を実行します。 |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetDescription](./getdescription/)(T) | 指定された値を持つ列挙定数の名前を返します。 |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetName](./getname/)(T) | 指定された値を持つ列挙定数の名前を返します。 |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() | **E** のすべてのメンバーの名前を含む配列を返します。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() | 列挙型の基になる型を返します。 |
| static [ArrayPtr](../arrayptr/)\<E\> [GetValues](./getvalues/)() | **E** のすべてのメンバーを含む配列を返します。 |
| static **bool** [HasFlag](./hasflag/)(E, E) | 指定された列挙値のビット表現で、指定されたビットが設定されているかどうかを判定します。 |
| static **bool** [IsDefined](./isdefined/)(E) | 指定された値が列挙型 **E** のメンバーであるかどうかを判定します。 |
| static std::enable_if\<std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, **bool**\>::type [IsDefined](./isdefined/)(T) | 指定された値が列挙型 **T** のメンバーであるかどうかを判定します。 |
| static **bool** [IsDefined](./isdefined/)(const [String](../string/)\&) | 指定された名前を持つ値が列挙型 **E** のメンバーに含まれているかどうかを判定します。 |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | 指定された文字列を同等の列挙定数に変換します。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, E\&) | 指定された文字列を同等の列挙定数に変換しようとします。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**, E\&) | 指定された文字列を同等の列挙定数に変換しようとします。 |

## 型エイリアス

| 型エイリアス | 説明 |
| --- | --- |
| [UnderlyingType](./underlyingtype/) | 列挙型の基になる型の別名です。 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)