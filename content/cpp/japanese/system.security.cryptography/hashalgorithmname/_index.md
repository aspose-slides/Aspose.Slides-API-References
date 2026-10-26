---
title: HashAlgorithmName
second_title: Aspose.Slides for C++ API リファレンス
description: "ハッシュアルゴリズムの名前を表す文字列です。この型はスタック上に割り当て、値渡しまたは参照渡しで関数に渡すべきです。System::SmartPtr クラスを使用してこの型のオブジェクトを管理しないでください。"
type: docs
weight: 755
url: /ja/system.security.cryptography/hashalgorithmname/
---
## HashAlgorithmName 構造体


[String](../../system/string/) はハッシュアルゴリズムの名前を表します。この型はスタック上に割り当て、値渡しまたは参照渡しで関数に渡すべきです。[System::SmartPtr](../../system/smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。

```cpp
class HashAlgorithmName
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| **bool** [Equals](./equals/)(const [HashAlgorithmName](./)\&) const |  |
| static [HashAlgorithmName](./) [FromOid](./fromoid/)(const [String](../../system/string/)\&) | OID 値から [HashAlgorithmName](./) を作成します。 |
| static [HashAlgorithmName](./) [get_MD5](./get_md5/)() | [MD5](../md5/) を表す [HashAlgorithmName](./) を取得します。 |
| [String](../../system/string/) [get_Name](./get_name/)() const | アルゴリズム名の文字列表現を取得します。 |
| static [HashAlgorithmName](./) [get_SHA1](./get_sha1/)() | [SHA1](../sha1/) を表す [HashAlgorithmName](./) を取得します。 |
| static [HashAlgorithmName](./) [get_SHA256](./get_sha256/)() | [SHA256](../sha256/) を表す [HashAlgorithmName](./) を取得します。 |
| static [HashAlgorithmName](./) [get_SHA384](./get_sha384/)() | [SHA384](../sha384/) を表す [HashAlgorithmName](./) を取得します。 |
| static [HashAlgorithmName](./) [get_SHA512](./get_sha512/)() | [SHA512](../sha512/) を表す [HashAlgorithmName](./) を取得します。 |
| int [GetHashCode](./gethashcode/)() const |  |
|  [HashAlgorithmName](./hashalgorithmname/)() |  |
|  [HashAlgorithmName](./hashalgorithmname/)(const [String](../../system/string/)\&) | コンストラクタ。 |
| **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [HashAlgorithmName](./)\&) const |  |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [HashAlgorithmName](./)\& [operator=](./operator_equal/)(const [HashAlgorithmName](./)\&) |  |
| **bool** [operator==](./operator_equal_equal/)(const [HashAlgorithmName](./)\&) const |  |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| [String](../../system/string/) [ToString](./tostring/)() const | アルゴリズム名の文字列表現を取得します。 |
| static **bool** [TryFromOid](./tryfromoid/)(const [String](../../system/string/)\&, [HashAlgorithmName](./)\&) | OID 値から [HashAlgorithmName](./) の作成を試みます。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](./type/)() | [TimeSpan](../../system/timespan/) 構造体を表す [TypeInfo](../../system/typeinfo/) オブジェクトを返します。 |
## 参照

* 名前空間 [System::Security::Cryptography](../)
* ライブラリ [Aspose.Slides](../../)