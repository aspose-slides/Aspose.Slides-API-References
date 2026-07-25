---
title: Version
second_title: Aspose.Slides for C++ API リファレンス
description: "バージョン番号を表します。この型はスタック上に割り当て、値または参照で関数に渡すべきです。System::SmartPtr クラスを使用してこの型のオブジェクトを管理しないでください。"
type: docs
weight: 1470
url: /ja/system/version/
---
## Version クラス


バージョン番号を表します。この型はスタック上に割り当て、値または参照で関数に渡すべきです。[System::SmartPtr](../smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。

```cpp
class Version
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| int [CompareTo](./compareto/)(const [Version](./)\&) const | 現在のオブジェクトと指定されたオブジェクトが表すバージョンを比較します。 |
| **bool** [Equals](./equals/)(const [Version](./)\&) const | 現在のオブジェクトと指定されたオブジェクトが表すバージョン番号が等しいかどうかを判断します。 |
| int [get_Build](./get_build/)() const | ビルド番号を返します。 |
| int [get_Major](./get_major/)() const | メジャーバージョンを返します。 |
| **int16_t** [get_MajorRevision](./get_majorrevision/)() const | リビジョン番号の上位16ビット値を返します。 |
| int [get_Minor](./get_minor/)() const | マイナーバージョンを返します。 |
| **int16_t** [get_MinorRevision](./get_minorrevision/)() const | リビジョン番号の下位16ビット値を返します。 |
| int [get_Revision](./get_revision/)() const | リビジョン番号を返します。 |
| int [GetHashCode](./gethashcode/)() const | 現在のオブジェクトのハッシュコードを返します。 |
| static [Version](./) [Parse](./parse/)(const [String](../string/)\&) | [Version](./) クラスの同等インスタンスに、バージョン番号の文字列表現を変換します。 |
| [String](../string/) [ToString](./tostring/)() const | 現在のオブジェクトが表すバージョン番号の文字列表現を返します。 |
| [String](../string/) [ToString](./tostring/)(int) const | 現在のオブジェクトが表すバージョン番号の指定されたセクション数の文字列表現を返します。 |
|  [Version](./version/)(int, int, int, int) | 指定されたメジャー、マイナー、ビルド、およびリビジョン値を表すインスタンスを構築します。 |
|  [Version](./version/)(int, int, int) | 指定されたメジャー、マイナー、ビルド値を表すインスタンスを構築します。 |
|  [Version](./version/)(int, int) | 指定されたメジャーと値を表すインスタンスを構築します。 |
|  [Version](./version/)(const [String](../string/)\&) | 文字列として表されるバージョン番号を表すインスタンスを構築します。 |
|  [Version](./version/)() | バージョン番号 0.0.-1.-1 を表すインスタンスを構築します。 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)