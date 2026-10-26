---
title: EnumValues
second_title: Aspose.Slides for C++ APIリファレンス
description: 列挙型 E の列挙定数に関するメタ情報を提供します。
type: docs
weight: 794
url: /ja/system/enumvalues/
---
## EnumValues クラス

列挙型 **E** の列挙定数に関するメタ情報を提供します。

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```

### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| E | 列挙型の型 |
## メソッド

| Method | Description |
| --- | --- |
|  [EnumValues](./enumvalues/)() | インスタンスを構築します。 |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() const override | 列挙型 **E** のすべての名前を含む配列を返します。 |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](../enumvaluesbase/getnames/)(const [TypeInfo](../typeinfo/)\&) | 指定された列挙型の定数の名前の配列を取得します。 |
| const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() const override | 指定された列挙型の基になる型を返します。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | 指定された列挙型の基になる型を返します。 |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | 指定された名前の列挙定数のボックス化された値を返します。 |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(long) const override | 指定された値の列挙定数のボックス化された値を返します。 |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | 列挙型 **E** のすべての値を含む配列を返します。 |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | 指定された列挙型のすべての値を含む配列を返します。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | 指定された名前で、指定された列挙型の列挙定数の値を表すオブジェクトを返します。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | 指定された 64 ビット符号なし整数値を列挙メンバーに変換します。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | 整数値を持つ指定されたオブジェクトを列挙メンバーに変換します。 |
| virtual  [~EnumValues](./~enumvalues/)() | デストラクタ。 |

## 参照

* クラス [EnumValuesBase](../enumvaluesbase/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)