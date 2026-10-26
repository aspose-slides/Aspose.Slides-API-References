---
title: Guid
second_title: Aspose.Slides for C++ API リファレンス
description: "グローバルに一意な識別子を表します。この型はスタック上に割り当て、値渡しまたは参照渡しで関数に渡すべきです。System::SmartPtr クラスを使用してこの型のオブジェクトを管理しないでください。"
type: docs
weight: 885
url: /ja/system/guid/
---
## Guid クラス


現在のオブジェクトと指定されたオブジェクトが表す GUID を表します。この型はスタック上に割り当て、値渡しまたは参照渡しで関数に渡すべきです。[System::SmartPtr](../smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。

```cpp
class Guid
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| int [CompareTo](./compareto/)(const [Guid](./)\&) const | 現在のオブジェクトと指定されたオブジェクトが表す GUID の算術比較を実行します。 |
| **bool** [Equals](./equals/)(const [Guid](./)\&) const | 現在のオブジェクトと指定されたオブジェクトが表す GUID が等しいかどうかを判定します。 |
| int [GetHashCode](./gethashcode/)() const | 現在のオブジェクトのハッシュコードを返します。 |
|  [Guid](./guid/)() | すべてゼロの GUID を表すオブジェクトを構築します。 |
|  [Guid](./guid/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | 符号なし 8 ビット整数値の配列として指定された GUID を表すオブジェクトを構築します。 |
|  [Guid](./guid/)(const System::Details::ArrayView\<**uint8_t**\>\&) | 符号なし 8 ビット整数値の配列ビューとして指定された GUID を表すオブジェクトを構築します。 |
|  [Guid](./guid/)(const [String](../string/)\&) | 文字列として指定された GUID を表すオブジェクトを構築します。 |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | 指定された GUID コンポーネントから [Guid](./) クラスのインスタンスを構築します。 |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const System::Details::ArrayView\<**uint8_t**\>\&) | 指定された GUID コンポーネントから [Guid](./) クラスのインスタンスを構築します。 |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | 指定された符号なし整数とバイトから [Guid](./) クラスのインスタンスを構築します。 |
|  [Guid](./guid/)(**uint32_t**, **uint16_t**, **uint16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | 指定された符号なし整数とバイトから [Guid](./) クラスのインスタンスを構築します。 |
|  [Guid](./guid/)(const [Guid](./)\&) | 指定されたオブジェクトと同じ GUID を表すオブジェクトを構築します。 |
| static [Guid](./) [NewGuid](./newguid/)() | 新しい GUID を生成し、それを表す [Guid](./) オブジェクトを返します。 |
| **bool** [operator!=](./operator_not_equal/)(const [Guid](./)\&) const | 現在のオブジェクトと指定されたオブジェクトが表す GUID が等しくないかどうかを判定します。 |
| [Guid](./)\& [operator=](./operator_equal/)(const [Guid](./)\&) | 現在のオブジェクトに、指定された [Guid](./) オブジェクトが表す GUID 値を代入します。 |
| **bool** [operator==](./operator_equal_equal/)(const [Guid](./)\&) const | 現在のオブジェクトと指定されたオブジェクトが表す GUID が等しいかどうかを判定します。 |
| static [Guid](./) [Parse](./parse/)(const [String](../string/)\&) | 指定された文字列形式の GUID を同等の [Guid](./) オブジェクトに変換します。 |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)() const | 現在のオブジェクトが表す GUID をバイト配列に変換します。 |
| [String](../string/) [ToString](./tostring/)() const | 現在のオブジェクトが表す GUID を文字列形式に変換します。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | 現在のオブジェクトが表す GUID を、指定された文字列フォーマットで文字列形式に変換します。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | 現在のオブジェクトが表す GUID を、指定された文字列フォーマットと Culture を使用して文字列形式に変換します。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Guid](./)\&) | 指定された文字列を [Guid](./) オブジェクトに変換しようとします。 |
|  [~Guid](./~guid/)() | デストラクタ。 |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static [Empty](./empty/) | 値が 0 の GUID を表します。 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)