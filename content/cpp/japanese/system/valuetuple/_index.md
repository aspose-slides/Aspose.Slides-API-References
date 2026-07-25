---
title: ValueTuple
second_title: Aspose.Slides for C++ API リファレンス
description: ValueTuple データ構造を表すクラスです。
type: docs
weight: 1444
url: /ja/system/valuetuple/
---
## ValueTuple クラス


[ValueTuple](./) データ構造を表すクラスです。

```cpp
template<typename ...>class ValueTuple : public System::Details::BoxableObjectBase
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) | 現在のオブジェクトと指定されたオブジェクトが同一かどうかを判定します。 |
| **bool** [Equals](./equals/)(const [ValueTuple](./)\&) |  |
| **int32_t** [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() | [ValueTuple](./) オブジェクトのコンポーネントの値への参照を取得します。 |
| const std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() const | [ValueTuple](./) オブジェクトのコンポーネントの値を取得します。 |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [ValueTuple](./)\<OtherArgs...\>\&) |  |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [SharedPtr](../sharedptr/)\<T\>\&) | オブジェクトをこの値タプルに分解します。 |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTuple](./)\&) const |  |
| [System::String](../string/) [ToString](./tostring/)() const |  |
| tuple_t\& [tuple](./tuple/)() |  |
| const tuple_t\& [tuple](./tuple/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | [TypeInfo](../typeinfo/) オブジェクトへの参照を返します。これは [ValueTuple](./) クラスの型情報を表します。 |
|  [ValueTuple](./valuetuple/)() |  |
|  [ValueTuple](./valuetuple/)(Args...) | タプルオブジェクトを構築します。 |
## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)