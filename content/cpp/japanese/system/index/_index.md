---
title: Index
second_title: Aspose.Slides for C++ API リファレンス
description: "コレクション内のインデックスを表します。インデックスは先頭からでも末尾からでも指定できます。この型はスタック上に割り当て、値または参照で関数に渡すべきです。System::SmartPtr クラスを使用してこの型のオブジェクトを管理しないでください。"
type: docs
weight: 1015
url: /ja/system/index/
---
## インデックス クラス

コレクション内のインデックスを表します。インデックスは先頭からでも末尾からでも指定できます。この型はスタック上に割り当て、値または参照で関数に渡すべきです。[System::SmartPtr](../smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。

```cpp
class Index : public System::Details::BoxableObjectBase
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| **bool** [Equals](./equals/)(const [Index](./)\&) const | 現在のインスタンスと指定された [Index](./) が同じ位置かどうかを判断します。 |
| static constexpr [Index](./) [FromEnd](./fromend/)(**int32_t**) | コレクションの末尾からの位置を表す [Index](./) を作成します。 |
| static constexpr [Index](./) [get_End](./get_end/)() | コレクションの末尾を表す [Index](./) オブジェクトを取得します。 |
| constexpr **bool** [get_IsFromEnd](./get_isfromend/)() const | インデックスが末尾からかどうかを示す値を取得します。 |
| static constexpr [Index](./) [get_Start](./get_start/)() | コレクションの先頭を表す [Index](./) オブジェクトを取得します。 |
| constexpr **int32_t** [get_Value](./get_value/)() const | インデックス値を取得します。 |
| **int32_t** [GetHashCode](./gethashcode/)() const | 現在のインデックスのハッシュコードを返します。 |
| **int32_t** [GetOffset](./getoffset/)(**int32_t**) const | 現在の [Index](./) を指定された長さのコレクションの先頭からのオフセットに変換します。 |
| constexpr [Index](./index/)() | コレクションの先頭を表すインスタンスを構築します。 |
| constexpr [Index](./index/)(**int32_t**) | コレクションの先頭から指定された位置を表すインスタンスを構築します。 |
| constexpr [Index](./index/)(**int32_t**, **bool**) | 指定されたインデックスを表すインスタンスを構築します。 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)