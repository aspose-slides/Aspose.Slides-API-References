---
title: Range
second_title: Aspose.Slides for C++ API リファレンス
description: "開始インデックスと終了インデックスを持つ範囲を表します。この型はスタック上に割り当て、値または参照で関数に渡すべきです。System::SmartPtr クラスを使用してこの型のオブジェクトを管理しないでください。"
type: docs
weight: 1197
url: /ja/system/range/
---
## Range クラス


開始インデックスと終了インデックスを持つ範囲を表します。この型はスタック上に割り当て、値または参照で関数に渡すべきです。[System::SmartPtr](../smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。

```cpp
class Range : public System::Details::BoxableObjectBase
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static constexpr [Range](./) [EndAt](./endat/)(const [Index](../index/)\&) | コレクションの開始位置で始まり、指定された終了インデックスで終わる範囲を作成します。 |
| **bool** [Equals](./equals/)(const [Range](./)\&) const | 現在の範囲が指定された範囲と等しいかどうかを判断します。 |
| static constexpr [Range](./) [get_All](./get_all/)() | [Range](./) を返します。これはコレクション全体を表します。 |
| const [Index](../index/)\& [get_End](./get_end/)() const | End インデックスを取得します。 |
| const [Index](../index/)\& [get_Start](./get_start/)() const | Start インデックスを取得します。 |
| **int32_t** [GetHashCode](./gethashcode/)() const | 現在の範囲のハッシュコードを返します。 |
| [System::ValueTuple](../valuetuple/)\<**int32_t**, **int32_t**\> [GetOffsetAndLength](./getoffsetandlength/)(**int32_t**) const | 指定されたコレクション長さに対する、0 ベースの開始オフセットと長さを計算します。 |
| constexpr [Range](./range/)() | 空の範囲を構築します。 |
| constexpr [Range](./range/)(const [Index](../index/)\&, const [Index](../index/)\&) | [Range](./) を、指定された開始および終了インデックスから構築します。 |
| static constexpr [Range](./) [StartAt](./startat/)(const [Index](../index/)\&) | 指定された開始インデックスで始まり、コレクションの末尾まで拡張する範囲を作成します。 |
## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)