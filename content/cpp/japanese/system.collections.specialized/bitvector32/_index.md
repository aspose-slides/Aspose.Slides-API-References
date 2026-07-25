---
title: BitVector32
second_title: Aspose.Slides for C++ API リファレンス
description: 32 ビットのストレージに対して、簡単な整数または Boolean アクセスが可能なシンプルで軽量なビットベクターを提供します。
type: docs
weight: 1
url: /ja/system.collections.specialized/bitvector32/
---
## BitVector32 クラス

簡単な整数または[Boolean](../../system/boolean/)アクセスで 32 ビットのストレージを扱えるシンプルな軽量ビットベクターを提供します。

```cpp
class BitVector32
```

## メソッド

| メソッド | 説明 |
| --- | --- |
|  [BitVector32](./bitvector32/)() | [BitVector32](./) の新しい空のインスタンスを初期化します。 |
|  [BitVector32](./bitvector32/)(**int32_t**) | [BitVector32](./) 構造体の新しいインスタンスを、指定された内部データで初期化します。 |
|  [BitVector32](./bitvector32/)(const [BitVector32](./)\&) | [BitVector32](./) 構造体の新しいインスタンスを、指定された値の情報で初期化します。 |
| static **int32_t** [CreateMask](./createmask/)() | シリーズの最初のマスクを作成します。 |
| static **int32_t** [CreateMask](./createmask/)(**int32_t**) | シリーズの次のマスクを作成します。 |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**) | シリーズの最初のセクションを、指定された最大値で作成します。 |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**, **BitVector32::Section**) | シリーズの次のセクションを、指定された最大値で作成します。 |
| **bool** [Equals](./equals/)(const [BitVector32](./)\&) | 指定されたオブジェクトが現在のオブジェクトと同じかどうかを判定します。 |
| **int32_t** [get_Data](./get_data/)() | このビットベクターに格納されている生データを返します。 |
| **int32_t** [GetHashCode](./gethashcode/)() const | 現在のオブジェクトのハッシュコードを返します。 |
| **bool** [idx_get](./idx_get/)(**int32_t**) | 指定されたすべてのビットが設定されているかどうかを示す値を取得します。 |
| **int32_t** [idx_get](./idx_get/)(**BitVector32::Section**) | 指定されたセクションの値を取得します。 |
| void [idx_set](./idx_set/)(**int32_t**, **bool**) | 指定されたすべてのビットが設定されているかどうかを示す値を設定します。 |
| void [idx_set](./idx_set/)(**BitVector32::Section**, **int32_t**) | 指定されたセクションの値を設定します。 |
| static [String](../../system/string/) [ToString](./tostring/)(const [BitVector32](./)\&) | 値パラメーターで表される値を文字列に変換します。 |
| [String](../../system/string/) [ToString](./tostring/)() const | 現在のオブジェクトで表される値を文字列に変換します。 |

## 参照

* 名前空間 [System::Collections::Specialized](../)
* ライブラリ [Aspose.Slides](../../)