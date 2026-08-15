---
title: Convert
second_title: "Aspose.Slides for C++ API 參考"
description: "此結構包含執行將一種型別的值轉換為另一種型別的值的方法。此型別應在堆疊上分配，並以值或參考方式傳遞給函式。絕不要使用 System::SmartPtr 類別來管理此型別的物件。"
type: docs
weight: 1561
url: /zh-hant/system/convert/
---
## 轉換結構


此結構包含執行從一種型別的值轉換為另一種型別的值的方法。此型別應在堆疊上配置，並以值或參考傳遞給函式。切勿使用 [System::SmartPtr](../smartptr/) 類別來管理此型別的物件。

```cpp
class Convert
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&) | 未實作。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64CharArray](./frombase64chararray/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | 將以 Unicode 字元陣列中範圍表示的 base-64 編碼資料解碼。 |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64String](./frombase64string/)(const [String](../string/)\&) | 將以字串表示的 base-64 編碼資料解碼。 |
| static [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | 傳回表示指定裝箱值型別的 TypeCode 值。 |
| static std::enable_if_t<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\> [IsDBNull](./isdbnull/)(const T\&) | 未實作。 |
| static **bool** [IsDBNull](./isdbnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 未實作。偽實作，檢查值是否為 nullptr。 |
| static Target [To](./to/)(const Source\&) |  |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, **bool**) | 將指定位元組陣列中範圍的元素以 Base-64 編碼，並將編碼資料儲存為 Unicode 字元陣列。 |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, [Base64FormattingOptions](../base64formattingoptions/)) | 將指定位元組陣列中範圍的元素以 Base-64 編碼，並將編碼資料儲存為 Unicode 字元陣列。 |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**) | 將指定位元組陣列中的元素以 Base-64 編碼，並以字串形式傳回編碼資料。 |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, **bool**) | 將指定位元組陣列中範圍的元素以 Base-64 編碼，並以字串形式傳回編碼資料。 |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, [Base64FormattingOptions](../base64formattingoptions/)) | 將指定位元組陣列中的元素以 Base-64 編碼，並以字串形式傳回編碼資料。 |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, [Base64FormattingOptions](../base64formattingoptions/)) | 將指定位元組陣列中範圍的元素以 Base-64 編碼，並以字串形式傳回編碼資料。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**bool**) | 傳回指定的布林值。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint8_t**) | 將指定的 8 位元無號整數轉換為等價的布林值。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int8_t**) | 將指定的 8 位元有號整數轉換為等價的布林值。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint16_t**) | 將指定的 16 位元無號整數轉換為等價的布林值。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int16_t**) | 將指定的 16 位元有號整數轉換為等價的布林值。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint32_t**) | 將指定的 32 位元無號整數轉換為等價的布林值。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int32_t**) | 將指定的 32 位元有號整數轉換為等價的布林值。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint64_t**) | 將指定的 64 位元無號整數轉換為等價的布林值。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int64_t**) | 將指定的 64 位元有號整數轉換為等價的布林值。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**float**) | 將指定的 float 數字轉換為等價的布林值。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**double**) | 將指定的 double 數字轉換為等價的布林值。 |
| static **bool** [ToBoolean](./toboolean/)(const [Decimal](../decimal/)\&) | 將指定的十進位數字轉換為等價的布林值。 |
| static **bool** [ToBoolean](./toboolean/)(char_t) | 不支援轉換。總是拋出 InvalidCastException。 |
| static **bool** [ToBoolean](./toboolean/)([DateTime](../datetime/)) | 不支援轉換。總是拋出 InvalidCastException。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(std::nullptr_t) | 將指定的 null 字串轉換為等價的布林值。 |
| static **bool** [ToBoolean](./toboolean/)(const char_t *) | 將指定的 C 字串轉換為 bool 型別的值。 |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&) | 將指定的字串轉換為 bool 型別的值。 |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的字串轉換為 bool 型別的值。 |
| static **bool** [ToBoolean](./toboolean/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的裝箱值轉換為等價的布林值。 |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**bool**) | 將指定的布林值轉換為等價的 8 位元無號整數。 |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**uint8_t**) | 傳回指定的 8 位元無號整數。 |
| static **uint8_t** [ToByte](./tobyte/)(**int8_t**) | 將指定的 8 位元有號整數轉換為等價的 8 位元無號整數。 |
| static **uint8_t** [ToByte](./tobyte/)(**uint16_t**) | 將指定的 16 位元無號整數轉換為等價的 8 位元無號整數。 |
| static **uint8_t** [ToByte](./tobyte/)(**int16_t**) | 將指定的 16 位元有號整數轉換為等價的 8 位元無號整數。 |
| static **uint8_t** [ToByte](./tobyte/)(**uint32_t**) | 將指定的 32 位元無號整數轉換為等價的 8 位元無號整數。 |
| static **uint8_t** [ToByte](./tobyte/)(**int32_t**) | 將指定的 32 位元有號整數轉換為等價的 8 位元無號整數。 |
| static **uint8_t** [ToByte](./tobyte/)(**uint64_t**) | 將指定的 64 位元無號整數轉換為等價的 8 位元無號整數。 |
| static **uint8_t** [ToByte](./tobyte/)(**int64_t**) | 將指定的 64 位元有號整數轉換為等價的 8 位元無號整數。 |
| static **uint8_t** [ToByte](./tobyte/)(**float**) | 將指定的 float 數字轉換為等價的 8 位元無號整數。 |
| static **uint8_t** [ToByte](./tobyte/)(**double**) | 將指定的 double 數字轉換為等價的 8 位元無號整數。 |
| static **uint8_t** [ToByte](./tobyte/)(const [Decimal](../decimal/)\&) | 將指定的十進位數字轉換為等價的 8 位元無號整數。 |
| static **uint8_t** [ToByte](./tobyte/)(char_t) | 將指定的 Unicode 字元轉換為等價的 8 位元無號整數。 |
| static **uint8_t** [ToByte](./tobyte/)([DateTime](../datetime/)) | 不支援轉換。總是拋出 InvalidCastException。 |
| static constexpr **uint8_t** [ToByte](./tobyte/)(std::nullptr_t) | 將指定的 null 字串轉換為等價的 8 位元無號整數值。 |
| static **uint8_t** [ToByte](./tobyte/)(const char_t *) | 將包含數字字串表示的 C 字串轉換為等價的 8 位元無號整數值。 |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&) | 將包含數字字串表示的字串轉換為等價的 8 位元無號整數值。 |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, int) | 將指定進位的數字字串表示的字串轉換為等價的 8 位元無號整數值。 |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式資訊，將包含數字字串表示的字串轉換為等價的 8 位元無號整數值。 |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式資訊與數字樣式，將包含數字字串表示的字串轉換為等價的 8 位元無號整數值。 |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)([Enum](../enum/)) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的裝箱值轉換為等價的 8 位元無號整數值。 |
| static char_t [ToChar](./tochar/)(**bool**) | 不支援轉換。總是拋出 InvalidCastException。 |
| static constexpr char_t [ToChar](./tochar/)(**uint8_t**) | 將指定的 8 位元無號整數轉換為等價的 Unicode 字元。 |
| static char_t [ToChar](./tochar/)(**int8_t**) | 將指定的 8 位元有號整數轉換為等價的 Unicode 字元。 |
| static constexpr char_t [ToChar](./tochar/)(**uint16_t**) | 將指定的 16 位元無號整數轉換為等價的 Unicode 字元。 |
| static char_t [ToChar](./tochar/)(**int16_t**) | 將指定的 16 位元有號整數轉換為等價的 Unicode 字元。 |
| static char_t [ToChar](./tochar/)(**uint32_t**) | 將指定的 32 位元無號整數轉換為等價的 Unicode 字元。 |
| static char_t [ToChar](./tochar/)(**int32_t**) | 將指定的 32 位元有號整數轉換為等價的 Unicode 字元。 |
| static char_t [ToChar](./tochar/)(**uint64_t**) | 將指定的 64 位元無號整數轉換為等價的 Unicode 字元。 |
| static char_t [ToChar](./tochar/)(**int64_t**) | 將指定的 64 位元有號整數轉換為等價的 Unicode 字元。 |
| static char_t [ToChar](./tochar/)(**float**) | 不支援轉換。總是拋出 InvalidCastException。 |
| static char_t [ToChar](./tochar/)(**double**) | 不支援轉換。總是拋出 InvalidCastException。 |
| static char_t [ToChar](./tochar/)(const [Decimal](../decimal/)\&) | 不支援轉換。總是拋出 InvalidCastException。 |
| static constexpr char_t [ToChar](./tochar/)(char_t) | 傳回指定的 Unicode 字元。 |
| static char_t [ToChar](./tochar/)([DateTime](../datetime/)) | 不支援轉換。總是拋出 InvalidCastException。 |
| static char_t [ToChar](./tochar/)(const char_t *) | 將指定 C 字串的首且唯一字元轉換為 char_t 值。 |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&) | 將指定字串的首且唯一字元轉換為 char_t 值。 |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定字串的首且唯一字元轉換為 char_t 值。 |
| static char_t [ToChar](./tochar/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的裝箱值轉換為等價的 Unicode 字元。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**bool**) | 不支援轉換。總是拋出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint8_t**) | 不支援轉換。總是拋出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int8_t**) | 不支援轉換。總是拋出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint16_t**) | 不支援轉換。總是拋出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int16_t**) | 不支援轉換。總是拋出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint32_t**) | 不支援轉換。總是拋出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int32_t**) | 不支援轉換。總是拋出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint64_t**) | 不支援轉換。總是拋出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int64_t**) | 不支援轉換。總是拋出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**float**) | 不支援轉換。總是拋出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**double**) | 不支援轉換。總是拋出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [Decimal](../decimal/)\&) | 不支援轉換。總是拋出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(char_t) | 不支援轉換。總是拋出 InvalidCastException。 |
| static constexpr [DateTime](../datetime/) [ToDateTime](./todatetime/)([DateTime](../datetime/)) | 傳回指定的日期和時間。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&) | 將指定的字串轉換為 [DateTime](../datetime/) 類別的實例。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的字串依照提供的格式資訊轉換為 [DateTime](../datetime/) 類別的實例。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的箱裝值轉換為等效的 [DateTime](../datetime/) 值。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**bool**) | 將指定的布林值轉換為等效的十進位數字。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint8_t**) | 將指定的 8 位元無號整數轉換為等效的十進位數字。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int8_t**) | 將指定的 8 位元有號整數轉換為等效的十進位數字。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint16_t**) | 將指定的 16 位元無號整數轉換為等效的十進位數字。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int16_t**) | 將指定的 16 位元有號整數轉換為等效的十進位數字。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint32_t**) | 將指定的 32 位元無號整數轉換為等效的十進位數字。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int32_t**) | 將指定的 32 位元有號整數轉換為等效的十進位數字。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint64_t**) | 將指定的 64 位元無號整數轉換為等效的十進位數字。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int64_t**) | 將指定的 64 位元有號整數轉換為等效的十進位數字。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**float**) | 將指定的 float 數字轉換為等效的十進位數字。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**double**) | 將指定的 double 數字轉換為等效的十進位數字。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [Decimal](../decimal/)\&) | 傳回指定的十進位數字。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(char_t) | 不支援轉換。總是拋出 InvalidCastException。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)([DateTime](../datetime/)) | 不支援轉換。總是拋出 InvalidCastException。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(std::nullptr_t) | 將指定的 null 字串轉換為等效的 [Decimal](../decimal/) 值。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const char_t *) | 將包含數字字串表示的 c 字串轉換為等效的 [Decimal](../decimal/) 值。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&) | 將包含數字字串表示的字串轉換為等效的 [Decimal](../decimal/) 值。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將包含數字字串表示的字串依照提供的格式資訊轉換為等效的 [Decimal](../decimal/) 值。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將包含數字字串表示的字串依指定的數字樣式與格式資訊轉換為等效的 [Decimal](../decimal/) 值。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的箱裝值轉換為等效的 [Decimal](../decimal/) 值。 |
| static constexpr **double** [ToDouble](./todouble/)(**bool**) | 將指定的布林值轉換為等效的雙精度浮點數。 |
| static constexpr **double** [ToDouble](./todouble/)(**uint8_t**) | 將指定的 8 位元無號整數轉換為等效的雙精度浮點數。 |
| static constexpr **double** [ToDouble](./todouble/)(**int8_t**) | 將指定的 8 位元有號整數轉換為等效的雙精度浮點數。 |
| static constexpr **double** [ToDouble](./todouble/)(**uint16_t**) | 將指定的 16 位元無號整數轉換為等效的雙精度浮點數。 |
| static constexpr **double** [ToDouble](./todouble/)(**int16_t**) | 將指定的 16 位元有號整數轉換為等效的雙精度浮點數。 |
| static constexpr **double** [ToDouble](./todouble/)(**uint32_t**) | 將指定的 32 位元無號整數轉換為等效的雙精度浮點數。 |
| static constexpr **double** [ToDouble](./todouble/)(**int32_t**) | 將指定的 32 位元有號整數轉換為等效的雙精度浮點數。 |
| static constexpr **double** [ToDouble](./todouble/)(**uint64_t**) | 將指定的 64 位元無號整數轉換為等效的雙精度浮點數。 |
| static constexpr **double** [ToDouble](./todouble/)(**int64_t**) | 將指定的 64 位元有號整數轉換為等效的雙精度浮點數。 |
| static constexpr **double** [ToDouble](./todouble/)(**float**) | 將指定的單精度數字轉換為等效的雙精度浮點數。 |
| static constexpr **double** [ToDouble](./todouble/)(**double**) | 傳回指定的 double 數字。 |
| static **double** [ToDouble](./todouble/)(const [Decimal](../decimal/)\&) | 將指定的十進位數字轉換為等效的雙精度浮點數。 |
| static **double** [ToDouble](./todouble/)(char_t) | 不支援轉換。總是拋出 InvalidCastException。 |
| static **double** [ToDouble](./todouble/)([DateTime](../datetime/)) | 不支援轉換。總是拋出 InvalidCastException。 |
| static constexpr **double** [ToDouble](./todouble/)(std::nullptr_t) | 將指定的 null 字串轉換為等效的雙精度浮點值。 |
| static **double** [ToDouble](./todouble/)(const char_t *) | 將包含數字字串表示的 c 字串轉換為等效的雙精度浮點值。 |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&) | 將包含數字字串表示的字串轉換為等效的雙精度浮點值。 |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將包含數字字串表示的字串依提供的格式資訊轉換為等效的雙精度浮點值。 |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將包含數字字串表示的字串依提供的格式資訊與數字樣式轉換為等效的雙精度浮點值。 |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的箱裝值轉換為雙精度浮點值。若箱裝值的類型為 [String](../string/)，則在轉換過程中使用指定的字串格式。 |
| static constexpr **int16_t** [ToInt16](./toint16/)(**bool**) | 將指定的布林值轉換為等效的 16 位元有號整數。 |
| static constexpr **int16_t** [ToInt16](./toint16/)(**uint8_t**) | 將指定的 8 位元無號整數轉換為等效的 16 位元有號整數。 |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int8_t**) | 將指定的 8 位元有號整數轉換為等效的 16 位元有號整數。 |
| static **int16_t** [ToInt16](./toint16/)(**uint16_t**) | 將指定的 16 位元無號整數轉換為等效的 16 位元有號整數。 |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int16_t**) | 傳回指定的 16 位元有號整數。 |
| static **int16_t** [ToInt16](./toint16/)(**uint32_t**) | 將指定的 32 位元無號整數轉換為等效的 16 位元有號整數。 |
| static **int16_t** [ToInt16](./toint16/)(**int32_t**) | 將指定的 32 位元有號整數轉換為等效的 16 位元有號整數。 |
| static **int16_t** [ToInt16](./toint16/)(**uint64_t**) | 將指定的 64 位元無號整數轉換為等效的 16 位元有號整數。 |
| static **int16_t** [ToInt16](./toint16/)(**int64_t**) | 將指定的 64 位元有號整數轉換為等效的 16 位元有號整數。 |
| static **int16_t** [ToInt16](./toint16/)(**float**) | 將指定的 float 數字轉換為等效的 16 位元有號整數。 |
| static **int16_t** [ToInt16](./toint16/)(**double**) | 將指定的 double 數字轉換為等效的 16 位元有號整數。 |
| static **int16_t** [ToInt16](./toint16/)(const [Decimal](../decimal/)\&) | 將指定的十進位數字轉換為等效的 16 位元有號整數。 |
| static **int16_t** [ToInt16](./toint16/)(char_t) | 將指定的 Unicode 字元轉換為等效的 16 位元有號整數。 |
| static **int16_t** [ToInt16](./toint16/)([DateTime](../datetime/)) | 不支援轉換。總是拋出 InvalidCastException。 |
| static constexpr **int16_t** [ToInt16](./toint16/)(std::nullptr_t) | 將指定的 null 字串轉換為等效的 16 位元整數值。 |
| static **int16_t** [ToInt16](./toint16/)(const char_t *) | 將包含數字字串表示的 c 字串轉換為等效的 16 位元整數值。 |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&) | 將包含數字字串表示的字串轉換為等效的 16 位元整數值。 |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, int) | 將指定基數下的數字字串表示的字串轉換為等效的 16 位元整數值。 |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將包含數字字串表示的字串依提供的格式資訊轉換為等效的 16 位元整數值。 |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將包含數字字串表示的字串依提供的格式資訊與數字樣式轉換為等效的 16 位元整數值。 |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)([Enum](../enum/)) |  |
| static **int16_t** [ToInt16](./toint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的箱裝值轉換為等效的 16 位元整數值。 |
| static constexpr int [ToInt32](./toint32/)(**bool**) | 將指定的布林值轉換為等效的 32 位元有號整數。 |
| static constexpr int [ToInt32](./toint32/)(**uint8_t**) | 將指定的 8 位元無號整數轉換為等效的 32 位元有號整數。 |
| static constexpr int [ToInt32](./toint32/)(**int8_t**) | 將指定的 8 位元有號整數轉換為等效的 32 位元有號整數。 |
| static constexpr int [ToInt32](./toint32/)(**uint16_t**) | 將指定的 16 位元無號整數轉換為等效的 32 位元有號整數。 |
| static constexpr int [ToInt32](./toint32/)(**int16_t**) | 將指定的 16 位元有號整數轉換為等效的 32 位元有號整數。 |
| static int [ToInt32](./toint32/)(**uint32_t**) | 將指定的 32 位元無號整數轉換為等效的 32 位元有號整數。 |
| static constexpr int [ToInt32](./toint32/)(**int32_t**) | 傳回指定的 32 位元有號整數。 |
| static int [ToInt32](./toint32/)(**uint64_t**) | 將指定的 64 位元無號整數轉換為等效的 32 位元有號整數。 |
| static int [ToInt32](./toint32/)(**int64_t**) | 將指定的 64 位元有號整數轉換為等效的 32 位元有號整數。 |
| static int [ToInt32](./toint32/)(**float**) | 將指定的單精度浮點數轉換為等效的 32 位元有號整數。 |
| static int [ToInt32](./toint32/)(**double**) | 將指定的雙精度浮點數轉換為等效的 32 位元有號整數。 |
| static int [ToInt32](./toint32/)(const [Decimal](../decimal/)\&) | 將指定的十進位數字轉換為等效的 32 位元有號整數。 |
| static constexpr int [ToInt32](./toint32/)(char_t) | 將指定的 Unicode 字元轉換為等效的 32 位元有號整數。 |
| static int [ToInt32](./toint32/)([DateTime](../datetime/)) | 不支援轉換。始終拋出 InvalidCastException。 |
| static constexpr int [ToInt32](./toint32/)(std::nullptr_t) | 將指定的 null 字串轉換為等效的 32 位元整數值。 |
| static int [ToInt32](./toint32/)(const char_t *) | 將指定的含有數字字串表示的 C 字串轉換為等效的 32 位元整數值。 |
| static int [ToInt32](./toint32/)(const [String](../string/)\&) | 將指定的含有數字字串表示的字串轉換為等效的 32 位元整數值。 |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, int) | 將指定的以指定基數表示的數字字串轉換為等效的 32 位元整數值。 |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的含有數字字串表示的字串，使用提供的格式化資訊，轉換為等效的 32 位元整數值。 |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的含有數字字串表示的字串，使用提供的格式化資訊及數字樣式，轉換為等效的 32 位元整數值。 |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [ToInt32](./toint32/)([Enum](../enum/)) |  |
| static int [ToInt32](./toint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的箱裝值轉換為等效的 32 位元整數值。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**bool**) | 將指定的布林值轉換為等效的 64 位元有號整數。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint8_t**) | 將指定的 8 位元無號整數轉換為等效的 64 位元有號整數。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int8_t**) | 將指定的 8 位元有號整數轉換為等效的 64 位元有號整數。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint16_t**) | 將指定的 16 位元無號整數轉換為等效的 64 位元有號整數。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int16_t**) | 將指定的 16 位元有號整數轉換為等效的 64 位元有號整數。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint32_t**) | 將指定的 32 位元無號整數轉換為等效的 64 位元有號整數。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int32_t**) | 將指定的 32 位元有號整數轉換為等效的 64 位元有號整數。 |
| static **int64_t** [ToInt64](./toint64/)(**uint64_t**) | 將指定的 64 位元無號整數轉換為等效的 64 位元有號整數。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int64_t**) | 傳回指定的 64 位元有號整數。 |
| static **int64_t** [ToInt64](./toint64/)(**float**) | 將指定的單精度浮點數轉換為等效的 64 位元有號整數。 |
| static **int64_t** [ToInt64](./toint64/)(**double**) | 將指定的雙精度浮點數轉換為等效的 64 位元有號整數。 |
| static **int64_t** [ToInt64](./toint64/)(const [Decimal](../decimal/)\&) | 將指定的十進位數字轉換為等效的 64 位元有號整數。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(char_t) | 將指定的 Unicode 字元轉換為等效的 64 位元有號整數。 |
| static **int64_t** [ToInt64](./toint64/)([DateTime](../datetime/)) | 不支援轉換。始終拋出 InvalidCastException。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(std::nullptr_t) | 將指定的 null 字串轉換為等效的 int 64 位元整數值。 |
| static **int64_t** [ToInt64](./toint64/)(const char_t *) | 將指定的含有數字字串表示的 C 字串轉換為等效的 64 位元整數值。 |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&) | 將指定的含有數字字串表示的字串轉換為等效的 64 位元整數值。 |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, int) | 將指定的以指定基數表示的數字字串轉換為等效的 64 位元整數值。 |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的含有數字字串表示的字串，使用提供的格式化資訊，轉換為等效的 64 位元整數值。 |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的含有數字字串表示的字串，使用提供的格式化資訊及數字樣式，轉換為等效的 64 位元整數值。 |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)([Enum](../enum/)) |  |
| static **int64_t** [ToInt64](./toint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的箱裝值轉換為等效的 64 位元整數值。 |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**bool**) | 將指定的布林值轉換為等效的 8 位元有號整數。 |
| static **int8_t** [ToSByte](./tosbyte/)(**uint8_t**) | 將指定的 8 位元無號整數轉換為等效的 8 位元有號整數。 |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**int8_t**) | 傳回指定的 8 位元有號整數。 |
| static **int8_t** [ToSByte](./tosbyte/)(**uint16_t**) | 將指定的 16 位元無號整數轉換為等效的 8 位元有號整數。 |
| static **int8_t** [ToSByte](./tosbyte/)(**int16_t**) | 將指定的 16 位元有號整數轉換為等效的 8 位元有號整數。 |
| static **int8_t** [ToSByte](./tosbyte/)(**uint32_t**) | 將指定的 32 位元無號整數轉換為等效的 8 位元有號整數。 |
| static **int8_t** [ToSByte](./tosbyte/)(**int32_t**) | 將指定的 32 位元有號整數轉換為等效的 8 位元有號整數。 |
| static **int8_t** [ToSByte](./tosbyte/)(**uint64_t**) | 將指定的 64 位元無號整數轉換為等效的 8 位元有號整數。 |
| static **int8_t** [ToSByte](./tosbyte/)(**int64_t**) | 將指定的 64 位元有號整數轉換為等效的 8 位元有號整數。 |
| static **int8_t** [ToSByte](./tosbyte/)(**float**) | 將指定的單精度浮點數轉換為等效的 8 位元有號整數。 |
| static **int8_t** [ToSByte](./tosbyte/)(**double**) | 將指定的雙精度浮點數轉換為等效的 8 位元有號整數。 |
| static **int8_t** [ToSByte](./tosbyte/)(const [Decimal](../decimal/)\&) | 將指定的十進位數字轉換為等效的 8 位元有號整數。 |
| static **int8_t** [ToSByte](./tosbyte/)(char_t) | 將指定的 Unicode 字元轉換為等效的 8 位元有號整數。 |
| static **int8_t** [ToSByte](./tosbyte/)([DateTime](../datetime/)) | 不支援轉換。始終拋出 InvalidCastException。 |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(std::nullptr_t) | 將指定的 null 字串轉換為等效的 8 位元整數值。 |
| static **int8_t** [ToSByte](./tosbyte/)(const char_t *) | 將指定的含有數字字串表示的 C 字串轉換為等效的 8 位元整數值。 |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&) | 將指定的含有數字字串表示的字串轉換為等效的 8 位元整數值。 |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, int) | 將指定的以指定基數表示的數字字串轉換為等效的 8 位元整數值。 |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的含有數字字串表示的字串，使用提供的格式化資訊，轉換為等效的 8 位元無號整數值。 |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的含有數字字串表示的字串，使用提供的格式化資訊及數字樣式，轉換為等效的 8 位元整數值。 |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)([Enum](../enum/)) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的箱裝值轉換為等效的 8 位元整數值。 |
| static constexpr **float** [ToSingle](./tosingle/)(**bool**) | 將指定的布林值轉換為等效的單精度浮點數。 |
| static constexpr **float** [ToSingle](./tosingle/)(**uint8_t**) | 將指定的 8 位元無號整數轉換為等效的單精度浮點數。 |
| static constexpr **float** [ToSingle](./tosingle/)(**int8_t**) | 將指定的 8 位元有號整數轉換為等效的單精度浮點數。 |
| static constexpr **float** [ToSingle](./tosingle/)(**uint16_t**) | 將指定的 16 位元無號整數轉換為等效的單精度浮點數。 |
| static constexpr **float** [ToSingle](./tosingle/)(**int16_t**) | 將指定的 16 位元有號整數轉換為等效的單精度浮點數。 |
| static constexpr **float** [ToSingle](./tosingle/)(**uint32_t**) | 將指定的 32 位元無號整數轉換為等效的單精度浮點數。 |
| static constexpr **float** [ToSingle](./tosingle/)(**int32_t**) | 將指定的 32 位元有號整數轉換為等效的單精度浮點數。 |
| static constexpr **float** [ToSingle](./tosingle/)(**uint64_t**) | 將指定的 64 位元無號整數轉換為等效的單精度浮點數。 |
| static constexpr **float** [ToSingle](./tosingle/)(**int64_t**) | 將指定的 64 位元有號整數轉換為等效的單精度浮點數。 |
| static constexpr **float** [ToSingle](./tosingle/)(**float**) | 傳回指定的浮點數。 |
| static constexpr **float** [ToSingle](./tosingle/)(**double**) | 將指定的雙精度數字轉換為等效的單精度浮點數。 |
| static **float** [ToSingle](./tosingle/)(const [Decimal](../decimal/)\&) | 將指定的十進位數字轉換為等效的單精度浮點數。 |
| static **float** [ToSingle](./tosingle/)(char_t) | 不支援轉換。總是拋出 InvalidCastException。 |
| static **float** [ToSingle](./tosingle/)([DateTime](../datetime/)) | 不支援轉換。總是拋出 InvalidCastException。 |
| static constexpr **float** [ToSingle](./tosingle/)(std::nullptr_t) | 將指定的空字串轉換為等效的單精度浮點值。 |
| static **float** [ToSingle](./tosingle/)(const char_t *) | 將包含數字字串表示的指定 C 字串轉換為等效的單精度浮點值。 |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&) | 將包含數字字串表示的指定字串轉換為等效的單精度浮點值。 |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式資訊，將包含數字字串表示的指定字串轉換為等效的單精度浮點值。 |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式資訊和數字樣式，將包含數字字串表示的指定字串轉換為等效的單精度浮點值。 |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的裝箱值轉換為單精度浮點值。 |
| static [String](../string/) [ToString](./tostring/)(**int8_t**) | 將指定的值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**) | 將指定的值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**int16_t**) | 將指定的值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**) | 將指定的值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**int32_t**) | 將指定的值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**) | 將指定的值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**int64_t**) | 將指定的值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**) | 將指定的值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**float**) | 將指定的值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**double**) | 將指定的值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&) | 將指定的值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/)) | 將指定的值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用特定文化的格式資訊，將指定的值轉換為字串。 |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用特定文化的格式資訊，將指定的值轉換為字串。 |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用特定文化的格式資訊，將指定的值轉換為字串。 |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用特定文化的格式資訊，將指定的值轉換為字串。 |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用特定文化的格式資訊，將指定的值轉換為字串。 |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用特定文化的格式資訊，將指定的值轉換為字串。 |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用特定文化的格式資訊，將指定的值轉換為字串。 |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用特定文化的格式資訊，將指定的值轉換為字串。 |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用特定文化的格式資訊，將指定的值轉換為字串。 |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用特定文化的格式資訊，將指定的值轉換為字串。 |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用特定文化的格式資訊，將指定的值轉換為字串。 |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用特定文化的格式資訊，將指定的值轉換為字串。 |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的字串格式以及由指定的 [IFormatProvider](../iformatprovider/) 物件提供的特定文化格式資訊，將指定的值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的字串格式以及由指定的 [IFormatProvider](../iformatprovider/) 物件提供的特定文化格式資訊，將指定的值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的字串格式以及由指定的 [IFormatProvider](../iformatprovider/) 物件提供的特定文化格式資訊，將指定的值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的字串格式以及由指定的 [IFormatProvider](../iformatprovider/) 物件提供的特定文化格式資訊，將指定的值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的字串格式以及由指定的 [IFormatProvider](../iformatprovider/) 物件提供的特定文化格式資訊，將指定的值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的字串格式以及由指定的 [IFormatProvider](../iformatprovider/) 物件提供的特定文化格式資訊，將指定的值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的值轉換為其字串表示形式，使用由指定的 [IFormatProvider](../iformatprovider/) 物件提供的指定字串格式和文化特定的格式資訊。 |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的值轉換為其字串表示形式，使用由指定的 [IFormatProvider](../iformatprovider/) 物件提供的指定字串格式和文化特定的格式資訊。 |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的值轉換為其字串表示形式，使用由指定的 [IFormatProvider](../iformatprovider/) 物件提供的指定字串格式和文化特定的格式資訊。 |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的值轉換為其字串表示形式，使用由指定的 [IFormatProvider](../iformatprovider/) 物件提供的指定字串格式和文化特定的格式資訊。 |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的值轉換為其字串表示形式，使用由指定的 [IFormatProvider](../iformatprovider/) 物件提供的指定字串格式和文化特定的格式資訊。 |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的值轉換為其字串表示形式，使用由指定的 [IFormatProvider](../iformatprovider/) 物件提供的指定字串格式和文化特定的格式資訊。 |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&) | 將指定的值轉換為字串。 |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&, const [String](../string/)\&) | 將指定的值使用指定的字串格式轉換為字串。 |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), std::nullptr_t) | 將指定的 Unicode 字元陣列轉換為字串。 |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的 Unicode 字元陣列轉換為字串，使用由指定的 [IFormatProvider](../iformatprovider/) 物件提供的文化特定格式資訊。 |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) | 傳回指定的值；不執行轉換。 |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 傳回指定的值；不執行轉換。 |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 傳回指定的值；不執行轉換。 |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | 傳回指定的值；不執行轉換。 |
| static [String](../string/) [ToString](./tostring/)(char_t, std::nullptr_t) | 傳回指定的值；不執行轉換。 |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 傳回指定的值；不執行轉換。 |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 傳回指定的值；不執行轉換。 |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 傳回指定的值；不執行轉換。 |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 傳回指定的值；不執行轉換。 |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, std::nullptr_t) | 傳回指定的值；不執行轉換。 |
| static [String](../string/) [ToString](./tostring/)(**bool**, std::nullptr_t) | 將指定的布林值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的布林值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 將指定的布林值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | 將指定的布林值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的布林值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 將指定的布林值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, std::nullptr_t) | 將指定的布林值轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, int) | 將指定的整數值依指定的進位制轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, int) | 將指定的整數值依指定的進位制轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, int) | 將指定的整數值依指定的進位制轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, int) | 將指定的整數值依指定的進位制轉換為其字串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的裝箱值轉換為其字串表示形式。若裝箱值的類型為 [String](../string/)，則在轉換過程中使用指定的字串格式。 |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**bool**) | 將指定的布林值轉換為等效的 16 位元無號整數。 |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint8_t**) | 將指定的 8 位元無號整數轉換為等效的 16 位元無號整數。 |
| static **uint16_t** [ToUInt16](./touint16/)(**int8_t**) | 將指定的 8 位元有號整數轉換為等效的 16 位元無號整數。 |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint16_t**) | 傳回指定的 16 位元無號整數。 |
| static **uint16_t** [ToUInt16](./touint16/)(**int16_t**) | 將指定的 16 位元有號整數轉換為等效的 16 位元無號整數。 |
| static **uint16_t** [ToUInt16](./touint16/)(**uint32_t**) | 將指定的 32 位元無號整數轉換為等效的 16 位元無號整數。 |
| static **uint16_t** [ToUInt16](./touint16/)(**int32_t**) | 將指定的 32 位元有號整數轉換為等效的 16 位元無號整數。 |
| static **uint16_t** [ToUInt16](./touint16/)(**uint64_t**) | 將指定的 64 位元無號整數轉換為等效的 16 位元無號整數。 |
| static **uint16_t** [ToUInt16](./touint16/)(**int64_t**) | 將指定的 64 位元有號整數轉換為等效的 16 位元無號整數。 |
| static **uint16_t** [ToUInt16](./touint16/)(**float**) | 將指定的 float 數字轉換為等效的 16 位元無號整數。 |
| static **uint16_t** [ToUInt16](./touint16/)(**double**) | 將指定的 double 數字轉換為等效的 16 位元無號整數。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [Decimal](../decimal/)\&) | 將指定的十進位數字轉換為等效的 16 位元無號整數。 |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(char_t) | 將指定的 Unicode 字元轉換為等效的 16 位元無號整數。 |
| static **uint16_t** [ToUInt16](./touint16/)([DateTime](../datetime/)) | 不支援轉換。總是拋出 InvalidCastException。 |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(std::nullptr_t) | 將指定的空字串轉換為等效的 16 位元無號整數值。 |
| static **uint16_t** [ToUInt16](./touint16/)(const char_t *) | 將包含數字字串表示的 C 字串轉換為等效的 16 位元無號整數值。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&) | 將包含數字字串表示的字串轉換為等效的 16 位元無號整數值。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, int) | 將指定進位制中數字字串表示的字串轉換為等效的 16 位元無號整數值。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式資訊，將包含數字字串表示的字串轉換為等效的 16 位元無號整數值。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式資訊和數字樣式，將包含數字字串表示的字串轉換為等效的 16 位元無號整數值。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)([Enum](../enum/)) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的裝箱值轉換為等效的 16 位元無號整數值。 |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**bool**) | 將指定的布林值轉換為等效的 32 位元無號整數。 |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint8_t**) | 將指定的 8 位元無號整數轉換為等效的 32 位元無號整數。 |
| static **uint32_t** [ToUInt32](./touint32/)(**int8_t**) | 將指定的 8 位元有號整數轉換為等效的 32 位元無號整數。 |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint16_t**) | 將指定的 16 位元無號整數轉換為等效的 32 位元無號整數。 |
| static **uint32_t** [ToUInt32](./touint32/)(**int16_t**) | 將指定的 16 位元有號整數轉換為等效的 32 位元無號整數。 |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint32_t**) | 傳回指定的 32 位元無號整數。 |
| static **uint32_t** [ToUInt32](./touint32/)(**int32_t**) | 將指定的 32 位有號整數轉換為等價的 32 位無號整數。 |
| static **uint32_t** [ToUInt32](./touint32/)(**uint64_t**) | 將指定的 64 位無號整數轉換為等價的 32 位無號整數。 |
| static **uint32_t** [ToUInt32](./touint32/)(**int64_t**) | 將指定的 64 位有號整數轉換為等價的 32 位無號整數。 |
| static **uint32_t** [ToUInt32](./touint32/)(**float**) | 將指定的 float 數字轉換為等價的 32 位無號整數。 |
| static **uint32_t** [ToUInt32](./touint32/)(**double**) | 將指定的 double 數字轉換為等價的 32 位無號整數。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [Decimal](../decimal/)\&) | 將指定的十進位數字轉換為等價的 32 位無號整數。 |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(char_t) | 將指定的 Unicode 字元轉換為等價的 32 位無號整數。 |
| static **uint32_t** [ToUInt32](./touint32/)([DateTime](../datetime/)) | 不支援轉換。始終拋出 InvalidCastException。 |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(std::nullptr_t) | 將指定的 null 字串轉換為等價的 32 位無號整數值。 |
| static **uint32_t** [ToUInt32](./touint32/)(const char_t *) | 將指定的 c 字串（其內容為數字的字串表示形式）轉換為等價的 32 位無號整數值。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&) | 將指定的字串（其內容為數字的字串表示形式）轉換為等價的 32 位無號整數值。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, int) | 將指定基底的字串（其內容為數字的字串表示形式）轉換為等價的 32 位無號整數值。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的字串（其內容為數字的字串表示形式）依據提供的格式資訊轉換為等價的 32 位無號整數值。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的字串（其內容為數字的字串表示形式）依據提供的格式資訊與數字樣式轉換為等價的 32 位無號整數值。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)([Enum](../enum/)) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的盒裝值轉換為等價的 32 位無號整數值。 |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**bool**) | 將指定的布林值轉換為等價的 64 位無號整數。 |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint8_t**) | 將指定的 8 位無號整數轉換為等價的 64 位無號整數。 |
| static **uint64_t** [ToUInt64](./touint64/)(**int8_t**) | 將指定的 8 位有號整數轉換為等價的 64 位無號整數。 |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint16_t**) | 將指定的 16 位無號整數轉換為等價的 64 位無號整數。 |
| static **uint64_t** [ToUInt64](./touint64/)(**int16_t**) | 將指定的 16 位有號整數轉換為等價的 64 位無號整數。 |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint32_t**) | 將指定的 32 位無號整數轉換為等價的 64 位無號整數。 |
| static **uint64_t** [ToUInt64](./touint64/)(**int32_t**) | 將指定的 32 位有號整數轉換為等價的 64 位無號整數。 |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint64_t**) | 傳回指定的 64 位無號整數。 |
| static **uint64_t** [ToUInt64](./touint64/)(**int64_t**) | 將指定的 64 位有號整數轉換為等價的 64 位無號整數。 |
| static **uint64_t** [ToUInt64](./touint64/)(**float**) | 將指定的 float 數字轉換為等價的 64 位無號整數。 |
| static **uint64_t** [ToUInt64](./touint64/)(**double**) | 將指定的 double 數字轉換為等價的 64 位無號整數。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [Decimal](../decimal/)\&) | 將指定的十進位數字轉換為等價的 64 位無號整數。 |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(char_t) | 將指定的 Unicode 字元轉換為等價的 64 位無號整數。 |
| static **uint64_t** [ToUInt64](./touint64/)([DateTime](../datetime/)) | 不支援轉換。始終拋出 InvalidCastException。 |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(std::nullptr_t) | 將指定的 null 字串轉換為等價的 64 位無號整數值。 |
| static **uint64_t** [ToUInt64](./touint64/)(const char_t *) | 將指定的 c 字串（其內容為數字的字串表示形式）轉換為等價的 64 位無號整數值。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&) | 將指定的字串（其內容為數字的字串表示形式）轉換為等價的 64 位無號整數值。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, int) | 將指定基底的字串（其內容為數字的字串表示形式）轉換為等價的 64 位無號整數值。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的字串（其內容為數字的字串表示形式）依據提供的格式資訊轉換為等價的 64 位無號整數值。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的字串（其內容為數字的字串表示形式）依據提供的格式資訊與數字樣式轉換為等價的 64 位無號整數值。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)([Enum](../enum/)) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將指定的盒裝值轉換為等價的 64 位無號整數值。 |
## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)