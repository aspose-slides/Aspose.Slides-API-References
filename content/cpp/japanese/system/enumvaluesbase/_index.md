---
title: EnumValuesBase
second_title: Aspose.Slides for C++ API リファレンス
description: 列挙型のメタ情報を表すクラスの基底クラスです。
type: docs
weight: 807
url: /ja/system/enumvaluesbase/
---
## EnumValuesBase クラス


列挙型のメタ情報を表すクラスの基底クラスです。

```cpp
class EnumValuesBase
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)(const [TypeInfo](../typeinfo/)\&) | 指定された列挙体の定数名の配列を取得します。 |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | 指定された列挙体の基底型を返します。 |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)(const [TypeInfo](../typeinfo/)\&) | 指定された列挙型のすべての値を含む配列を返します。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | 指定された列挙型の指定された名前を持つ列挙定数の値を表すオブジェクトを返します。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | 指定された64ビット符号なし整数値を列挙メンバーに変換します。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | 整数値を持つ指定されたオブジェクトを列挙メンバーに変換します。 |
## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)