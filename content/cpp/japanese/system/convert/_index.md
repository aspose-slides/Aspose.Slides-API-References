---
title: Convert
second_title: Aspose.Slides for C++ API リファレンス
description: "ある型の値を別の型の値に変換するメソッドを含む構造体です。この型はスタック上に割り当て、値渡しまたは参照渡しで関数に渡すべきです。System::SmartPtr クラスを使用してこの型のオブジェクトを管理しないでください。"
type: docs
weight: 1561
url: /ja/system/convert/
---
## 変換構造体

この構造体は、ある型の値を別の型の値に変換するメソッドを含んでいます。この型はスタック上に割り当て、値渡しまたは参照渡しで関数に渡すべきです。[System::SmartPtr](../smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。

```cpp
class Convert
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&) | 未実装です。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64CharArray](./frombase64chararray/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Unicode 文字の配列内の範囲として表された Base-64 エンコードされたデータをデコードします。 |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64String](./frombase64string/)(const [String](../string/)\&) | 文字列として表された Base-64 エンコードされたデータをデコードします。 |
| static [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | 指定されたボックス化された値の型を表す TypeCode 値を返します。 |
| static std::enable_if_t<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\> [IsDBNull](./isdbnull/)(const T\&) | 未実装です。 |
| static **bool** [IsDBNull](./isdbnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 未実装です。偽の実装で、値が nullptr かどうかを確認します。 |
| static Target [To](./to/)(const Source\&) |  |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, **bool**) | 指定されたバイト配列の要素範囲を Base-64 エンコードし、エンコードされたデータを Unicode 文字の配列として保存します。 |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, [Base64FormattingOptions](../base64formattingoptions/)) | 指定されたバイト配列の要素範囲を Base-64 エンコードし、エンコードされたデータを Unicode 文字の配列として保存します。 |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**) | 指定されたバイト配列の要素を Base-64 エンコードし、エンコードされたデータを文字列として返します。 |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, **bool**) | 指定されたバイト配列の要素を Base-64 エンコードし、エンコードされたデータを文字列として返します。 |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, [Base64FormattingOptions](../base64formattingoptions/)) | 指定されたバイト配列の要素を Base-64 エンコードし、エンコードされたデータを文字列として返します。 |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, [Base64FormattingOptions](../base64formattingoptions/)) | 指定されたバイト配列の要素を Base-64 エンコードし、エンコードされたデータを文字列として返します。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**bool**) | 指定されたブール値を返します。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint8_t**) | 指定された 8 ビット符号なし整数を同等のブール値に変換します。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int8_t**) | 指定された 8 ビット符号付き整数を同等のブール値に変換します。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint16_t**) | 指定された 16 ビット符号なし整数を同等のブール値に変換します。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int16_t**) | 指定された 16 ビット符号付き整数を同等のブール値に変換します。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint32_t**) | 指定された 32 ビット符号なし整数を同等のブール値に変換します。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int32_t**) | 指定された 32 ビット符号付き整数を同等のブール値に変換します。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint64_t**) | 指定された 64 ビット符号なし整数を同等のブール値に変換します。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int64_t**) | 指定された 64 ビット符号付き整数を同等のブール値に変換します。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**float**) | 指定された float 数値を同等のブール値に変換します。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**double**) | 指定された double 数値を同等のブール値に変換します。 |
| static **bool** [ToBoolean](./toboolean/)(const [Decimal](../decimal/)\&) | 指定された decimal 数値を同等のブール値に変換します。 |
| static **bool** [ToBoolean](./toboolean/)(char_t) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static **bool** [ToBoolean](./toboolean/)([DateTime](../datetime/)) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(std::nullptr_t) | 指定された null 文字列を同等のブール値に変換します。 |
| static **bool** [ToBoolean](./toboolean/)(const char_t *) | 指定された C 文字列を bool 型の値に変換します。 |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&) | 指定された文字列を bool 型の値に変換します。 |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された文字列を bool 型の値に変換します。 |
| static **bool** [ToBoolean](./toboolean/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定されたボックス化された値を同等のブール値に変換します。 |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**bool**) | 指定されたブール値を同等の 8 ビット符号なし整数に変換します。 |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**uint8_t**) | 指定された 8 ビット符号なし整数を返します。 |
| static **uint8_t** [ToByte](./tobyte/)(**int8_t**) | 指定された 8 ビット符号付き整数を同等の 8 ビット符号なし整数に変換します。 |
| static **uint8_t** [ToByte](./tobyte/)(**uint16_t**) | 指定された 16 ビット符号なし整数を同等の 8 ビット符号なし整数に変換します。 |
| static **uint8_t** [ToByte](./tobyte/)(**int16_t**) | 指定された 16 ビット符号付き整数を同等の 8 ビット符号なし整数に変換します。 |
| static **uint8_t** [ToByte](./tobyte/)(**uint32_t**) | 指定された 32 ビット符号なし整数を同等の 8 ビット符号なし整数に変換します。 |
| static **uint8_t** [ToByte](./tobyte/)(**int32_t**) | 指定された 32 ビット符号付き整数を同等の 8 ビット符号なし整数に変換します。 |
| static **uint8_t** [ToByte](./tobyte/)(**uint64_t**) | 指定された 64 ビット符号なし整数を同等の 8 ビット符号なし整数に変換します。 |
| static **uint8_t** [ToByte](./tobyte/)(**int64_t**) | 指定された 64 ビット符号付き整数を同等の 8 ビット符号なし整数に変換します。 |
| static **uint8_t** [ToByte](./tobyte/)(**float**) | 指定された float 数値を同等の 8 ビット符号なし整数に変換します。 |
| static **uint8_t** [ToByte](./tobyte/)(**double**) | 指定された double 数値を同等の 8 ビット符号なし整数に変換します。 |
| static **uint8_t** [ToByte](./tobyte/)(const [Decimal](../decimal/)\&) | 指定された decimal 数値を同等の 8 ビット符号なし整数に変換します。 |
| static **uint8_t** [ToByte](./tobyte/)(char_t) | 指定された Unicode 文字を同等の 8 ビット符号なし整数に変換します。 |
| static **uint8_t** [ToByte](./tobyte/)([DateTime](../datetime/)) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static constexpr **uint8_t** [ToByte](./tobyte/)(std::nullptr_t) | 指定された null 文字列を同等の符号なし 8 ビット整数値に変換します。 |
| static **uint8_t** [ToByte](./tobyte/)(const char_t *) | 数値の文字列表現を含む C 文字列を同等の符号なし 8 ビット整数値に変換します。 |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&) | 数値の文字列表現を含む文字列を同等の符号なし 8 ビット整数値に変換します。 |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, int) | 指定された基数で表された数値の文字列表現を含む文字列を同等の符号なし 8 ビット整数値に変換します。 |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 提供された書式情報を使用して、数値の文字列表現を含む文字列を同等の符号なし 8 ビット整数値に変換します。 |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 提供された書式情報と数値形式を使用して、数値の文字列表現を含む文字列を同等の符号なし 8 ビット整数値に変換します。 |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)([Enum](../enum/)) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定されたボックス化された値を同等の符号なし 8 ビット整数値に変換します。 |
| static char_t [ToChar](./tochar/)(**bool**) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static constexpr char_t [ToChar](./tochar/)(**uint8_t**) | 指定された 8 ビット符号なし整数を同等の Unicode 文字に変換します。 |
| static char_t [ToChar](./tochar/)(**int8_t**) | 指定された 8 ビット符号付き整数を同等の Unicode 文字に変換します。 |
| static constexpr char_t [ToChar](./tochar/)(**uint16_t**) | 指定された 16 ビット符号なし整数を同等の Unicode 文字に変換します。 |
| static char_t [ToChar](./tochar/)(**int16_t**) | 指定された 16 ビット符号付き整数を同等の Unicode 文字に変換します。 |
| static char_t [ToChar](./tochar/)(**uint32_t**) | 指定された 32 ビット符号なし整数を同等の Unicode 文字に変換します。 |
| static char_t [ToChar](./tochar/)(**int32_t**) | 指定された 32 ビット符号付き整数を同等の Unicode 文字に変換します。 |
| static char_t [ToChar](./tochar/)(**uint64_t**) | 指定された 64 ビット符号なし整数を同等の Unicode 文字に変換します。 |
| static char_t [ToChar](./tochar/)(**int64_t**) | 指定された 64 ビット符号付き整数を同等の Unicode 文字に変換します。 |
| static char_t [ToChar](./tochar/)(**float**) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static char_t [ToChar](./tochar/)(**double**) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static char_t [ToChar](./tochar/)(const [Decimal](../decimal/)\&) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static constexpr char_t [ToChar](./tochar/)(char_t) | 指定された Unicode 文字を返します。 |
| static char_t [ToChar](./tochar/)([DateTime](../datetime/)) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static char_t [ToChar](./tochar/)(const char_t *) | 指定された C 文字列の最初で唯一の文字を char_t 値に変換します。 |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&) | 指定された文字列の最初で唯一の文字を char_t 値に変換します。 |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された文字列の最初で唯一の文字を char_t 値に変換します。 |
| static char_t [ToChar](./tochar/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定されたボックス化された値を同等の Unicode 文字に変換します。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**bool**) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint8_t**) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int8_t**) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint16_t**) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int16_t**) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint32_t**) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int32_t**) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint64_t**) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int64_t**) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**float**) | 変換はサポートされていません。常に InvalidCastException がスローされます。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**double**) | 変換はサポートされていません。常に InvalidCastException がスローされます。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [Decimal](../decimal/)\&) | 変換はサポートされていません。常に InvalidCastException がスローされます。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(char_t) | 変換はサポートされていません。常に InvalidCastException がスローされます。 |
| static constexpr [DateTime](../datetime/) [ToDateTime](./todatetime/)([DateTime](../datetime/)) | 指定された日付と時刻を返します。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&) | 指定された文字列を [DateTime](../datetime/) クラスのインスタンスに変換します。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 提供された書式情報を使用して、指定された文字列を [DateTime](../datetime/) クラスのインスタンスに変換します。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定されたボックス化された値を同等の [DateTime](../datetime/) 値に変換します。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**bool**) | 指定されたブール値を同等の十進数に変換します。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint8_t**) | 指定された 8 ビット符号なし整数を同等の十進数に変換します。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int8_t**) | 指定された 8 ビット符号付き整数を同等の十進数に変換します。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint16_t**) | 指定された 16 ビット符号なし整数を同等の十進数に変換します。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int16_t**) | 指定された 16 ビット符号付き整数を同等の十進数に変換します。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint32_t**) | 指定された 32 ビット符号なし整数を同等の十進数に変換します。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int32_t**) | 指定された 32 ビット符号付き整数を同等の十進数に変換します。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint64_t**) | 指定された 64 ビット符号なし整数を同等の十進数に変換します。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int64_t**) | 指定された 64 ビット符号付き整数を同等の十進数に変換します。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**float**) | 指定された float 数値を同等の十進数に変換します。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**double**) | 指定された double 数値を同等の十進数に変換します。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [Decimal](../decimal/)\&) | 指定された十進数を返します。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(char_t) | 変換はサポートされていません。常に InvalidCastException がスローされます。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)([DateTime](../datetime/)) | 変換はサポートされていません。常に InvalidCastException がスローされます。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(std::nullptr_t) | 指定された null 文字列を同等の [Decimal](../decimal/) 値に変換します。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const char_t *) | 数値の文字列表現を含む指定された C 文字列を同等の [Decimal](../decimal/) 値に変換します。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&) | 数値の文字列表現を含む指定された文字列を同等の [Decimal](../decimal/) 値に変換します。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 提供された書式情報を使用して、数値の文字列表現を含む指定された文字列を同等の [Decimal](../decimal/) 値に変換します。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された数値書式と書式情報を使用して、数値の文字列表現を含む指定された文字列を同等の [Decimal](../decimal/) 値に変換します。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定されたボックス化された値を同等の [Decimal](../decimal/) 値に変換します。 |
| static constexpr **double** [ToDouble](./todouble/)(**bool**) | 指定されたブール値を同等の倍精度浮動小数点数に変換します。 |
| static constexpr **double** [ToDouble](./todouble/)(**uint8_t**) | 指定された 8 ビット符号なし整数を同等の倍精度浮動小数点数に変換します。 |
| static constexpr **double** [ToDouble](./todouble/)(**int8_t**) | 指定された 8 ビット符号付き整数を同等の倍精度浮動小数点数に変換します。 |
| static constexpr **double** [ToDouble](./todouble/)(**uint16_t**) | 指定された 16 ビット符号なし整数を同等の倍精度浮動小数点数に変換します。 |
| static constexpr **double** [ToDouble](./todouble/)(**int16_t**) | 指定された 16 ビット符号付き整数を同等の倍精度浮動小数点数に変換します。 |
| static constexpr **double** [ToDouble](./todouble/)(**uint32_t**) | 指定された 32 ビット符号なし整数を同等の倍精度浮動小数点数に変換します。 |
| static constexpr **double** [ToDouble](./todouble/)(**int32_t**) | 指定された 32 ビット符号付き整数を同等の倍精度浮動小数点数に変換します。 |
| static constexpr **double** [ToDouble](./todouble/)(**uint64_t**) | 指定された 64 ビット符号なし整数を同等の倍精度浮動小数点数に変換します。 |
| static constexpr **double** [ToDouble](./todouble/)(**int64_t**) | 指定された 64 ビット符号付き整数を同等の倍精度浮動小数点数に変換します。 |
| static constexpr **double** [ToDouble](./todouble/)(**float**) | 指定された単精度数値を同等の倍精度浮動小数点数に変換します。 |
| static constexpr **double** [ToDouble](./todouble/)(**double**) | 指定された double 値を返します。 |
| static **double** [ToDouble](./todouble/)(const [Decimal](../decimal/)\&) | 指定された十進数を同等の倍精度浮動小数点数に変換します。 |
| static **double** [ToDouble](./todouble/)(char_t) | 変換はサポートされていません。常に InvalidCastException がスローされます。 |
| static **double** [ToDouble](./todouble/)([DateTime](../datetime/)) | 変換はサポートされていません。常に InvalidCastException がスローされます。 |
| static constexpr **double** [ToDouble](./todouble/)(std::nullptr_t) | 指定された null 文字列を同等の倍精度浮動小数点値に変換します。 |
| static **double** [ToDouble](./todouble/)(const char_t *) | 数値の文字列表現を含む指定された C 文字列を同等の倍精度浮動小数点値に変換します。 |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&) | 数値の文字列表現を含む指定された文字列を同等の倍精度浮動小数点値に変換します。 |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 提供された書式情報を使用して、数値の文字列表現を含む指定された文字列を同等の倍精度浮動小数点値に変換します。 |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 提供された書式情報と数値書式を使用して、数値の文字列表現を含む指定された文字列を同等の倍精度浮動小数点値に変換します。 |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定されたボックス化された値を倍精度浮動小数点値に変換します。ボックス化された値の型が [String](../string/) の場合、変換時に指定された文字列フォーマットが使用されます。 |
| static constexpr **int16_t** [ToInt16](./toint16/)(**bool**) | 指定されたブール値を同等の 16 ビット符号付き整数に変換します。 |
| static constexpr **int16_t** [ToInt16](./toint16/)(**uint8_t**) | 指定された 8 ビット符号なし整数を同等の 16 ビット符号付き整数に変換します。 |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int8_t**) | 指定された 8 ビット符号付き整数を同等の 16 ビット符号付き整数に変換します。 |
| static **int16_t** [ToInt16](./toint16/)(**uint16_t**) | 指定された 16 ビット符号なし整数を同等の 16 ビット符号付き整数に変換します。 |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int16_t**) | 指定された 16 ビット符号付き整数を返します。 |
| static **int16_t** [ToInt16](./toint16/)(**uint32_t**) | 指定された 32 ビット符号なし整数を同等の 16 ビット符号付き整数に変換します。 |
| static **int16_t** [ToInt16](./toint16/)(**int32_t**) | 指定された 32 ビット符号付き整数を同等の 16 ビット符号付き整数に変換します。 |
| static **int16_t** [ToInt16](./toint16/)(**uint64_t**) | 指定された 64 ビット符号なし整数を同等の 16 ビット符号付き整数に変換します。 |
| static **int16_t** [ToInt16](./toint16/)(**int64_t**) | 指定された 64 ビット符号付き整数を同等の 16 ビット符号付き整数に変換します。 |
| static **int16_t** [ToInt16](./toint16/)(**float**) | 指定された float 数値を同等の 16 ビット符号付き整数に変換します。 |
| static **int16_t** [ToInt16](./toint16/)(**double**) | 指定された double 数値を同等の 16 ビット符号付き整数に変換します。 |
| static **int16_t** [ToInt16](./toint16/)(const [Decimal](../decimal/)\&) | 指定された十進数を同等の 16 ビット符号付き整数に変換します。 |
| static **int16_t** [ToInt16](./toint16/)(char_t) | 指定された Unicode 文字を同等の 16 ビット符号付き整数に変換します。 |
| static **int16_t** [ToInt16](./toint16/)([DateTime](../datetime/)) | 変換はサポートされていません。常に InvalidCastException がスローされます。 |
| static constexpr **int16_t** [ToInt16](./toint16/)(std::nullptr_t) | 指定された null 文字列を同等の 16 ビット整数値に変換します。 |
| static **int16_t** [ToInt16](./toint16/)(const char_t *) | 数値の文字列表現を含む指定された C 文字列を同等の 16 ビット整数値に変換します。 |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&) | 数値の文字列表現を含む指定された文字列を同等の 16 ビット整数値に変換します。 |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, int) | 指定された基数で数値の文字列表現を含む指定された文字列を同等の 16 ビット整数値に変換します。 |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 提供された書式情報を使用して、数値の文字列表現を含む指定された文字列を同等の 16 ビット整数値に変換します。 |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 提供された書式情報と数値書式を使用して、数値の文字列表現を含む指定された文字列を同等の 16 ビット整数値に変換します。 |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)([Enum](../enum/)) |  |
| static **int16_t** [ToInt16](./toint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定されたボックス化された値を同等の 16 ビット整数値に変換します。 |
| static constexpr int [ToInt32](./toint32/)(**bool**) | 指定されたブール値を同等の 32 ビット符号付き整数に変換します。 |
| static constexpr int [ToInt32](./toint32/)(**uint8_t**) | 指定された 8 ビット符号なし整数を同等の 32 ビット符号付き整数に変換します。 |
| static constexpr int [ToInt32](./toint32/)(**int8_t**) | 指定された 8 ビット符号付き整数を同等の 32 ビット符号付き整数に変換します。 |
| static constexpr int [ToInt32](./toint32/)(**uint16_t**) | 指定された 16 ビット符号なし整数を同等の 32 ビット符号付き整数に変換します。 |
| static constexpr int [ToInt32](./toint32/)(**int16_t**) | 指定された 16 ビット符号付き整数を同等の 32 ビット符号付き整数に変換します。 |
| static int [ToInt32](./toint32/)(**uint32_t**) | 指定された 32 ビット符号なし整数を同等の 32 ビット符号付き整数に変換します。 |
| static constexpr int [ToInt32](./toint32/)(**int32_t**) | 指定された 32 ビット符号付き整数を返します。 |
| static int [ToInt32](./toint32/)(**uint64_t**) | 指定された 64 ビット符号なし整数を同等の 32 ビット符号付き整数に変換します。 |
| static int [ToInt32](./toint32/)(**int64_t**) | 指定された 64 ビット符号付き整数を同等の 32 ビット符号付き整数に変換します。 |
| static int [ToInt32](./toint32/)(**float**) | 指定された float 値を同等の 32 ビット符号付き整数に変換します。 |
| static int [ToInt32](./toint32/)(**double**) | 指定された double 値を同等の 32 ビット符号付き整数に変換します。 |
| static int [ToInt32](./toint32/)(const [Decimal](../decimal/)\&) | 指定された decimal 数値を同等の 32 ビット符号付き整数に変換します。 |
| static constexpr int [ToInt32](./toint32/)(char_t) | 指定された Unicode 文字を同等の 32 ビット符号付き整数に変換します。 |
| static int [ToInt32](./toint32/)([DateTime](../datetime/)) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static constexpr int [ToInt32](./toint32/)(std::nullptr_t) | 指定された null 文字列を同等の 32 ビット整数値に変換します。 |
| static int [ToInt32](./toint32/)(const char_t *) | 数値の文字列表現を含む指定された C 文字列を同等の 32 ビット整数値に変換します。 |
| static int [ToInt32](./toint32/)(const [String](../string/)\&) | 数値の文字列表現を含む指定された文字列を同等の 32 ビット整数値に変換します。 |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, int) | 指定された基数で数値の文字列表現を含む文字列を同等の 32 ビット整数値に変換します。 |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 提供された書式情報を使用して、数値の文字列表現を含む指定された文字列を同等の 32 ビット整数値に変換します。 |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 提供された書式情報と数値スタイルを使用して、数値の文字列表現を含む指定された文字列を同等の 32 ビット整数値に変換します。 |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [ToInt32](./toint32/)([Enum](../enum/)) |  |
| static int [ToInt32](./toint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | ボックス化された値を同等の 32 ビット整数値に変換します。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**bool**) | 指定された boolean 値を同等の 64 ビット符号付き整数に変換します。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint8_t**) | 指定された 8 ビット符号なし整数を同等の 64 ビット符号付き整数に変換します。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int8_t**) | 指定された 8 ビット符号付き整数を同等の 64 ビット符号付き整数に変換します。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint16_t**) | 指定された 16 ビット符号なし整数を同等の 64 ビット符号付き整数に変換します。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int16_t**) | 指定された 16 ビット符号付き整数を同等の 64 ビット符号付き整数に変換します。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint32_t**) | 指定された 32 ビット符号なし整数を同等の 64 ビット符号付き整数に変換します。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int32_t**) | 指定された 32 ビット符号付き整数を同等の 64 ビット符号付き整数に変換します。 |
| static **int64_t** [ToInt64](./toint64/)(**uint64_t**) | 指定された 64 ビット符号なし整数を同等の 64 ビット符号付き整数に変換します。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int64_t**) | 指定された 64 ビット符号付き整数を返します。 |
| static **int64_t** [ToInt64](./toint64/)(**float**) | 指定された float 値を同等の 64 ビット符号付き整数に変換します。 |
| static **int64_t** [ToInt64](./toint64/)(**double**) | 指定された double 値を同等の 64 ビット符号付き整数に変換します。 |
| static **int64_t** [ToInt64](./toint64/)(const [Decimal](../decimal/)\&) | 指定された decimal 数値を同等の 64 ビット符号付き整数に変換します。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(char_t) | 指定された Unicode 文字を同等の 64 ビット符号付き整数に変換します。 |
| static **int64_t** [ToInt64](./toint64/)([DateTime](../datetime/)) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(std::nullptr_t) | 指定された null 文字列を同等の 64 ビット整数値に変換します。 |
| static **int64_t** [ToInt64](./toint64/)(const char_t *) | 数値の文字列表現を含む指定された C 文字列を同等の 64 ビット整数値に変換します。 |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&) | 数値の文字列表現を含む指定された文字列を同等の 64 ビット整数値に変換します。 |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, int) | 指定された基数で数値の文字列表現を含む文字列を同等の 64 ビット整数値に変換します。 |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 提供された書式情報を使用して、数値の文字列表現を含む指定された文字列を同等の 64 ビット整数値に変換します。 |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 提供された書式情報と数値スタイルを使用して、数値の文字列表現を含む指定された文字列を同等の 64 ビット整数値に変換します。 |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)([Enum](../enum/)) |  |
| static **int64_t** [ToInt64](./toint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | ボックス化された値を同等の 64 ビット整数値に変換します。 |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**bool**) | 指定された boolean 値を同等の 8 ビット符号付き整数に変換します。 |
| static **int8_t** [ToSByte](./tosbyte/)(**uint8_t**) | 指定された 8 ビット符号なし整数を同等の 8 ビット符号付き整数に変換します。 |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**int8_t**) | 指定された 8 ビット符号付き整数を返します。 |
| static **int8_t** [ToSByte](./tosbyte/)(**uint16_t**) | 指定された 16 ビット符号なし整数を同等の 8 ビット符号付き整数に変換します。 |
| static **int8_t** [ToSByte](./tosbyte/)(**int16_t**) | 指定された 16 ビット符号付き整数を同等の 8 ビット符号付き整数に変換します。 |
| static **int8_t** [ToSByte](./tosbyte/)(**uint32_t**) | 指定された 32 ビット符号なし整数を同等の 8 ビット符号付き整数に変換します。 |
| static **int8_t** [ToSByte](./tosbyte/)(**int32_t**) | 指定された 32 ビット符号付き整数を同等の 8 ビット符号付き整数に変換します。 |
| static **int8_t** [ToSByte](./tosbyte/)(**uint64_t**) | 指定された 64 ビット符号なし整数を同等の 8 ビット符号付き整数に変換します。 |
| static **int8_t** [ToSByte](./tosbyte/)(**int64_t**) | 指定された 64 ビット符号付き整数を同等の 8 ビット符号付き整数に変換します。 |
| static **int8_t** [ToSByte](./tosbyte/)(**float**) | 指定された float 値を同等の 8 ビット符号付き整数に変換します。 |
| static **int8_t** [ToSByte](./tosbyte/)(**double**) | 指定された double 値を同等の 8 ビット符号付き整数に変換します。 |
| static **int8_t** [ToSByte](./tosbyte/)(const [Decimal](../decimal/)\&) | 指定された decimal 数値を同等の 8 ビット符号付き整数に変換します。 |
| static **int8_t** [ToSByte](./tosbyte/)(char_t) | 指定された Unicode 文字を同等の 8 ビット符号付き整数に変換します。 |
| static **int8_t** [ToSByte](./tosbyte/)([DateTime](../datetime/)) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(std::nullptr_t) | 指定された null 文字列を同等の 8 ビット整数値に変換します。 |
| static **int8_t** [ToSByte](./tosbyte/)(const char_t *) | 数値の文字一覧表現を含む指定された C 文字列を同等の 8 ビット整数値に変換します。 |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&) | 数値の文字列表現を含む指定された文字列を同等の 8 ビット整数値に変換します。 |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, int) | 指定された基数で数値の文字一覧表現を含む文字列を同等の 8 ビット整数値に変換します。 |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 提供された書式情報を使用して、数値の文字列表現を含む指定された文字列を同等の符号なし 8 ビット整数値に変換します。 |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 提供された書式情報と数値スタイルを使用して、数値の文字列表現を含む指定された文字列を同等の 8 ビット整数値に変換します。 |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)([Enum](../enum/)) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | ボックス化された値を同等の 8 ビット整数値に変換します。 |
| static constexpr **float** [ToSingle](./tosingle/)(**bool**) | 指定された boolean 値を同等の単精度浮動小数点数に変換します。 |
| static constexpr **float** [ToSingle](./tosingle/)(**uint8_t**) | 指定された 8 ビット符号なし整数を同等の単精度浮動小数点数に変換します。 |
| static constexpr **float** [ToSingle](./tosingle/)(**int8_t**) | 指定された 8 ビット符号付き整数を同等の単精度浮動小数点数に変換します。 |
| static constexpr **float** [ToSingle](./tosingle/)(**uint16_t**) | 指定された 16 ビット符号なし整数を同等の単精度浮動小数点数に変換します。 |
| static constexpr **float** [ToSingle](./tosingle/)(**int16_t**) | 指定された 16 ビット符号付き整数を同等の単精度浮動小数点数に変換します。 |
| static constexpr **float** [ToSingle](./tosingle/)(**uint32_t**) | 指定された 32 ビット符号なし整数を同等の単精度浮動小数点数に変換します。 |
| static constexpr **float** [ToSingle](./tosingle/)(**int32_t**) | 指定された 32 ビット符号付き整数を同等の単精度浮動小数点数に変換します。 |
| static constexpr **float** [ToSingle](./tosingle/)(**uint64_t**) | 指定された 64 ビット符号なし整数を同等の単精度浮動小数点数に変換します。 |
| static constexpr **float** [ToSingle](./tosingle/)(**int64_t**) | 指定された 64 ビット符号付き整数を同等の単精度浮動小数点数に変換します。 |
| static constexpr **float** [ToSingle](./tosingle/)(**float**) | 指定された float 値を返します。 |
| static constexpr **float** [ToSingle](./tosingle/)(**double**) | 指定された倍精度数値を同等の単精度浮動小数点数に変換します。 |
| static **float** [ToSingle](./tosingle/)(const [Decimal](../decimal/)\&) | 指定された10進数を同等の単精度浮動小数点数に変換します。 |
| static **float** [ToSingle](./tosingle/)(char_t) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static **float** [ToSingle](./tosingle/)([DateTime](../datetime/)) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static constexpr **float** [ToSingle](./tosingle/)(std::nullptr_t) | 指定された null 文字列を同等の単精度浮動小数点値に変換します。 |
| static **float** [ToSingle](./tosingle/)(const char_t *) | 数値の文字列表現を含む指定された C 文字列を同等の単精度浮動小数点値に変換します。 |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&) | 数値の文字列表現を含む指定された文字列を同等の単精度浮動小数点値に変換します。 |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された文字列（数値の文字列表現を含む）を、提供された書式情報を使用して同等の単精度浮動小数点値に変換します。 |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された文字列（数値の文字列表現を含む）を、提供された書式情報と数値スタイルを使用して同等の単精度浮動小数点値に変換します。 |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定されたボックス化された値を単精度浮動小数点値に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**int8_t**) | 指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**) | 指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**int16_t**) | 指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**) | 指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**int32_t**) | 指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**) | 指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**int64_t**) | 指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**) | 指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**float**) | 指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**double**) | 指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&) | 指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/)) | 指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された値を、カルチャ固有の書式情報を使用して文字列に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された値を、カルチャ固有の書式情報を使用して文字列に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された値を、カルチャ固有の書式情報を使用して文字列に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された値を、カルチャ固有の書式情報を使用して文字列に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された値を、カルチャ固有の書式情報を使用して文字列に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された値を、カルチャ固有の書式情報を使用して文字列に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された値を、カルチャ固有の書式情報を使用して文字列に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された値を、カルチャ固有の書式情報を使用して文字列に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された値を、カルチャ固有の書式情報を使用して文字列に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された値を、カルチャ固有の書式情報を使用して文字列に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された値を、カルチャ固有の書式情報を使用して文字列に変換します。 |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された値を、カルチャ固有の書式情報を使用して文字列に変換します。 |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された [IFormatProvider](../iformatprovider/) オブジェクトが提供する文字列書式とカルチャ固有の書式情報を使用して、指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された [IFormatProvider](../iformatprovider/) オブジェクトが提供する文字列書式とカルチャ固有の書式情報を使用して、指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された [IFormatProvider](../iformatprovider/) オブジェクトが提供する文字列書式とカルチャ固有の書式情報を使用して、指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された [IFormatProvider](../iformatprovider/) オブジェクトが提供する文字列書式とカルチャ固有の書式情報を使用して、指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された [IFormatProvider](../iformatprovider/) オブジェクトが提供する文字列書式とカルチャ固有の書式情報を使用して、指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された [IFormatProvider](../iformatprovider/) オブジェクトが提供する文字列書式とカルチャ固有の書式情報を使用して、指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された値を、指定された文字列書式および [IFormatProvider](../iformatprovider/) オブジェクトが提供するカルチャ固有の書式情報を使用して文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された値を、指定された文字列書式および [IFormatProvider](../iformatprovider/) オブジェクトが提供するカルチャ固有の書式情報を使用して文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された値を、指定された文字列書式および [IFormatProvider](../iformatprovider/) オブジェクトが提供するカルチャ固有の書式情報を使用して文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された値を、指定された文字列書式および [IFormatProvider](../iformatprovider/) オブジェクトが提供するカルチャ固有の書式情報を使用して文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された値を、指定された文字列書式および [IFormatProvider](../iformatprovider/) オブジェクトが提供するカルチャ固有の書式情報を使用して文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された値を、指定された文字列書式および [IFormatProvider](../iformatprovider/) オブジェクトが提供するカルチャ固有の書式情報を使用して文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&) | 指定された値を文字列に変換します。 |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&, const [String](../string/)\&) | 指定された値を、指定された文字列書式を使用して文字列に変換します。 |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), std::nullptr_t) | 指定された Unicode 文字の配列を文字列に変換します。 |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された Unicode 文字の配列を、[IFormatProvider](../iformatprovider/) オブジェクトが提供するカルチャ固有の書式情報を使用して文字列に変換します。 |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) | 指定された値を返します。変換は行われません。 |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された値を返します。変換は行われません。 |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 指定された値を返します。変換は行われません。 |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | 指定された値を返します。変換は行われません。 |
| static [String](../string/) [ToString](./tostring/)(char_t, std::nullptr_t) | 指定された値を返します。変換は行われません。 |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された値を返します。変換は行われません。 |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 指定された値を返します。変換は行われません。 |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された値を返します。変換は行われません。 |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 指定された値を返します。変換は行われません。 |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, std::nullptr_t) | 指定された値を返します。変換は行われません。 |
| static [String](../string/) [ToString](./tostring/)(**bool**, std::nullptr_t) | 指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | 指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, std::nullptr_t) | 指定された値を文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, int) | 指定された整数値を、指定された基数で文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, int) | 指定された整数値を、指定された基数で文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, int) | 指定された整数値を、指定された基数で文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, int) | 指定された整数値を、指定された基数で文字列表現に変換します。 |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定されたボックス化された値を文字列表現に変換します。ボックス化された値の型が [String](../string/) の場合、指定された文字列書式が変換時に使用されます。 |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**bool**) | 指定されたブール値を同等の 16 ビット符号なし整数に変換します。 |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint8_t**) | 指定された 8 ビット符号なし整数を同等の 16 ビット符号なし整数に変換します。 |
| static **uint16_t** [ToUInt16](./touint16/)(**int8_t**) | 指定された 8 ビット符号付き整数を同等の 16 ビット符号なし整数に変換します。 |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint16_t**) | 指定された 16 ビット符号なし整数を返します。 |
| static **uint16_t** [ToUInt16](./touint16/)(**int16_t**) | 指定された 16 ビット符号付き整数を同等の 16 ビット符号なし整数に変換します。 |
| static **uint16_t** [ToUInt16](./touint16/)(**uint32_t**) | 指定された 32 ビット符号なし整数を同等の 16 ビット符号なし整数に変換します。 |
| static **uint16_t** [ToUInt16](./touint16/)(**int32_t**) | 指定された 32 ビット符号付き整数を同等の 16 ビット符号なし整数に変換します。 |
| static **uint16_t** [ToUInt16](./touint16/)(**uint64_t**) | 指定された 64 ビット符号なし整数を同等の 16 ビット符号なし整数に変換します。 |
| static **uint16_t** [ToUInt16](./touint16/)(**int64_t**) | 指定された 64 ビット符号付き整数を同等の 16 ビット符号なし整数に変換します。 |
| static **uint16_t** [ToUInt16](./touint16/)(**float**) | 指定された float 数値を同等の 16 ビット符号なし整数に変換します。 |
| static **uint16_t** [ToUInt16](./touint16/)(**double**) | 指定された double 数値を同等の 16 ビット符号なし整数に変換します。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [Decimal](../decimal/)\&) | 指定された decimal 数値を同等の 16 ビット符号なし整数に変換します。 |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(char_t) | 指定された Unicode 文字を同等の 16 ビット符号なし整数に変換します。 |
| static **uint16_t** [ToUInt16](./touint16/)([DateTime](../datetime/)) | 変換はサポートされていません。常に InvalidCastException がスローされます。 |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(std::nullptr_t) | 指定された null 文字列を同等の符号なし 16 ビット整数値に変換します。 |
| static **uint16_t** [ToUInt16](./touint16/)(const char_t *) | 数値の文字列表現を含む指定された C 文字列を同等の符号なし 16 ビット整数値に変換します。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&) | 数値の文字列表現を含む指定された文字列を同等の符号なし 16 ビット整数値に変換します。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, int) | 指定された基数での数値の文字列表現を含む指定された文字列を同等の符号なし 16 ビット整数値に変換します。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 提供された書式情報を使用して、数値の文字列表現を含む指定された文字列を同等の符号なし 16 ビット整数値に変換します。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 提供された書式情報と数値スタイルを使用して、数値の文字列表現を含む指定された文字列を同等の符号なし 16 ビット整数値に変換します。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)([Enum](../enum/)) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定されたボックス化された値を同等の符号なし 16 ビット整数値に変換します。 |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**bool**) | 指定されたブール値を同等の 32 ビット符号なし整数に変換します。 |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint8_t**) | 指定された 8 ビット符号なし整数を同等の 32 ビット符号なし整数に変換します。 |
| static **uint32_t** [ToUInt32](./touint32/)(**int8_t**) | 指定された 8 ビット符号付き整数を同等の 32 ビット符号なし整数に変換します。 |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint16_t**) | 指定された 16 ビット符号なし整数を同等の 32 ビット符号なし整数に変換します。 |
| static **uint32_t** [ToUInt32](./touint32/)(**int16_t**) | 指定された 16 ビット符号付き整数を同等の 32 ビット符号なし整数に変換します。 |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint32_t**) | 指定された 32 ビット符号なし整数を返します。 |
| static **uint32_t** [ToUInt32](./touint32/)(**int32_t**) | 指定された 32 ビット符号付き整数を同等の 32 ビット符号なし整数に変換します。 |
| static **uint32_t** [ToUInt32](./touint32/)(**uint64_t**) | 指定された 64 ビット符号なし整数を同等の 32 ビット符号なし整数に変換します。 |
| static **uint32_t** [ToUInt32](./touint32/)(**int64_t**) | 指定された 64 ビット符号付き整数を同等の 32 ビット符号なし整数に変換します。 |
| static **uint32_t** [ToUInt32](./touint32/)(**float**) | 指定された float 数値を同等の 32 ビット符号なし整数に変換します。 |
| static **uint32_t** [ToUInt32](./touint32/)(**double**) | 指定された double 数値を同等の 32 ビット符号なし整数に変換します。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [Decimal](../decimal/)\&) | 指定された decimal 数値を同等の 32 ビット符号なし整数に変換します。 |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(char_t) | 指定された unicode 文字を同等の 32 ビット符号なし整数に変換します。 |
| static **uint32_t** [ToUInt32](./touint32/)([DateTime](../datetime/)) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(std::nullptr_t) | 指定された null 文字列を同等の符号なし 32 ビット整数値に変換します。 |
| static **uint32_t** [ToUInt32](./touint32/)(const char_t *) | 数値の文字列表現を含む指定された c 文字列を同等の符号なし 32 ビット整数値に変換します。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&) | 数値の文字列表現を含む指定された文字列を同等の符号なし 32 ビット整数値に変換します。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, int) | 指定された基数で数値の文字列表現を含む文字列を同等の符号なし 32 ビット整数値に変換します。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 提供された書式情報を使用して、数値の文字列表現を含む指定された文字列を同等の符号なし 32 ビット整数値に変換します。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 提供された書式情報と数値形式を使用して、数値の文字列表現を含む指定された文字列を同等の符号なし 32 ビット整数値に変換します。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)([Enum](../enum/)) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定されたボックス化された値を同等の符号なし 32 ビット整数値に変換します。 |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**bool**) | 指定された boolean 値を同等の 64 ビット符号なし整数に変換します。 |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint8_t**) | 指定された 8 ビット符号なし整数を同等の 64 ビット符号なし整数に変換します。 |
| static **uint64_t** [ToUInt64](./touint64/)(**int8_t**) | 指定された 8 ビット符号付き整数を同等の 64 ビット符号なし整数に変換します。 |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint16_t**) | 指定された 16 ビット符号なし整数を同等の 64 ビット符号なし整数に変換します。 |
| static **uint64_t** [ToUInt64](./touint64/)(**int16_t**) | 指定された 16 ビット符号付き整数を同等の 64 ビット符号なし整数に変換します。 |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint32_t**) | 指定された 32 ビット符号なし整数を同等の 64 ビット符号なし整数に変換します。 |
| static **uint64_t** [ToUInt64](./touint64/)(**int32_t**) | 指定された 32 ビット符号付き整数を同等の 64 ビット符号なし整数に変換します。 |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint64_t**) | 指定された 64 ビット符号なし整数を返します。 |
| static **uint64_t** [ToUInt64](./touint64/)(**int64_t**) | 指定された 64 ビット符号付き整数を同等の 64 ビット符号なし整数に変換します。 |
| static **uint64_t** [ToUInt64](./touint64/)(**float**) | 指定された float 数値を同等の 64 ビット符号なし整数に変換します。 |
| static **uint64_t** [ToUInt64](./touint64/)(**double**) | 指定された double 数値を同等の 64 ビット符号なし整数に変換します。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [Decimal](../decimal/)\&) | 指定された decimal 数値を同等の 64 ビット符号なし整数に変換します。 |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(char_t) | 指定された unicode 文字を同等の 64 ビット符号なし整数に変換します。 |
| static **uint64_t** [ToUInt64](./touint64/)([DateTime](../datetime/)) | 変換はサポートされていません。常に InvalidCastException をスローします。 |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(std::nullptr_t) | 指定された null 文字列を同等の符号なし 64 ビット整数値に変換します。 |
| static **uint64_t** [ToUInt64](./touint64/)(const char_t *) | 数値の文字列表現を含む指定された c 文字列を同等の符号なし 64 ビット整数値に変換します。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&) | 数値の文字列表現を含む指定された文字列を同等の符号なし 64 ビット整数値に変換します。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, int) | 指定された基数で数値の文字列表現を含む文字列を同等の符号なし 64 ビット整数値に変換します。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 提供された書式情報を使用して、数値の文字列表現を含む指定された文字列を同等の符号なし 64 ビット整数値に変換します。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 提供された書式情報と数値形式を使用して、数値の文字列表現を含む指定された文字列を同等の符号なし 64 ビット整数値に変換します。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)([Enum](../enum/)) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定されたボックス化された値を同等の符号なし 64 ビット整数値に変換します。 |
## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)