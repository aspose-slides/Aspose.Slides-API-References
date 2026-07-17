---
title: Convert
second_title: Aspose.Slides for C++ API 参考
description: "包含执行将一种类型的值转换为另一种类型的值的方法的结构体。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 System::SmartPtr 类来管理此类型的对象。"
type: docs
weight: 1535
url: /zh/system/convert/
---
## 转换结构体

此结构体包含执行将一种类型的值转换为另一种类型的值的方法。该类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../smartptr/) 类来管理此类型的对象。

```cpp
class Convert
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&) | 未实现。 |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64CharArray](./frombase64chararray/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | 将表示为 Unicode 字符数组中范围的 Base-64 编码数据解码。 |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64String](./frombase64string/)(const [String](../string/)\&) | 将表示为字符串的 Base-64 编码数据解码。 |
| static [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | 返回表示指定装箱值类型的 TypeCode 值。 |
| static std::enable_if_t<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\> [IsDBNull](./isdbnull/)(const T\&) | 未实现。 |
| static **bool** [IsDBNull](./isdbnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 未实现。虚假实现，检查值是否为 nullptr。 |
| static Target [To](./to/)(const Source\&) |  |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, **bool**) | 对指定字节数组中的元素范围进行 Base-64 编码，并将编码数据存储为 Unicode 字符数组。 |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, [Base64FormattingOptions](../base64formattingoptions/)) | 对指定字节数组中的元素范围进行 Base-64 编码，并将编码数据存储为 Unicode 字符数组。 |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**) | 对指定字节数组中的元素进行 Base-64 编码，并以字符串形式返回编码数据。 |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, **bool**) | 对指定字节数组中的元素范围进行 Base-64 编码，并以字符串形式返回编码数据。 |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, [Base64FormattingOptions](../base64formattingoptions/)) | 对指定字节数组中的元素进行 Base-64 编码，并以字符串形式返回编码数据。 |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, [Base64FormattingOptions](../base64formattingoptions/)) | 对指定字节数组中的元素范围进行 Base-64 编码，并以字符串形式返回编码数据。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**bool**) | 返回指定的布尔值。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint8_t**) | 将指定的 8 位无符号整数转换为等效的布尔值。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int8_t**) | 将指定的 8 位有符号整数转换为等效的布尔值。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint16_t**) | 将指定的 16 位无符号整数转换为等效的布尔值。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int16_t**) | 将指定的 16 位有符号整数转换为等效的布尔值。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint32_t**) | 将指定的 32 位无符号整数转换为等效的布尔值。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int32_t**) | 将指定的 32 位有符号整数转换为等效的布尔值。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint64_t**) | 将指定的 64 位无符号整数转换为等效的布尔值。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int64_t**) | 将指定的 64 位有符号整数转换为等效的布尔值。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**float**) | 将指定的浮点数转换为等效的布尔值。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(**double**) | 将指定的双精度数转换为等效的布尔值。 |
| static **bool** [ToBoolean](./toboolean/)(const [Decimal](../decimal/)\&) | 将指定的十进制数转换为等效的布尔值。 |
| static **bool** [ToBoolean](./toboolean/)(char_t) | 不支持转换。始终抛出 InvalidCastException。 |
| static **bool** [ToBoolean](./toboolean/)([DateTime](../datetime/)) | 不支持转换。始终抛出 InvalidCastException。 |
| static constexpr **bool** [ToBoolean](./toboolean/)(std::nullptr_t) | 将指定的空字符串转换为等效的布尔值。 |
| static **bool** [ToBoolean](./toboolean/)(const char_t *) | 将指定的 C 字符串转换为 bool 类型的值。 |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&) | 将指定的字符串转换为 bool 类型的值。 |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 将指定的字符串转换为 bool 类型的值。 |
| static **bool** [ToBoolean](./toboolean/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 将指定的装箱值转换为等效的布尔值。 |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**bool**) | 将指定的布尔值转换为等效的 8 位无符号整数。 |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**uint8_t**) | 返回指定的 8 位无符号整数。 |
| static **uint8_t** [ToByte](./tobyte/)(**int8_t**) | 将指定的 8 位有符号整数转换为等效的 8 位无符号整数。 |
| static **uint8_t** [ToByte](./tobyte/)(**uint16_t**) | 将指定的 16 位无符号整数转换为等效的 8 位无符号整数。 |
| static **uint8_t** [ToByte](./tobyte/)(**int16_t**) | 将指定的 16 位有符号整数转换为等效的 8 位无符号整数。 |
| static **uint8_t** [ToByte](./tobyte/)(**uint32_t**) | 将指定的 32 位无符号整数转换为等效的 8 位无符号整数。 |
| static **uint8_t** [ToByte](./tobyte/)(**int32_t**) | 将指定的 32 位有符号整数转换为等效的 8 位无符号整数。 |
| static **uint8_t** [ToByte](./tobyte/)(**uint64_t**) | 将指定的 64 位无符号整数转换为等效的 8 位无符号整数。 |
| static **uint8_t** [ToByte](./tobyte/)(**int64_t**) | 将指定的 64 位有符号整数转换为等效的 8 位无符号整数。 |
| static **uint8_t** [ToByte](./tobyte/)(**float**) | 将指定的浮点数转换为等效的 8 位无符号整数。 |
| static **uint8_t** [ToByte](./tobyte/)(**double**) | 将指定的双精度数转换为等效的 8 位无符号整数。 |
| static **uint8_t** [ToByte](./tobyte/)(const [Decimal](../decimal/)\&) | 将指定的十进制数转换为等效的 8 位无符号整数。 |
| static **uint8_t** [ToByte](./tobyte/)(char_t) | 将指定的 Unicode 字符转换为等效的 8 位无符号整数。 |
| static **uint8_t** [ToByte](./tobyte/)([DateTime](../datetime/)) | 不支持转换。始终抛出 InvalidCastException。 |
| static constexpr **uint8_t** [ToByte](./tobyte/)(std::nullptr_t) | 将指定的空字符串转换为等效的 8 位无符号整数值。 |
| static **uint8_t** [ToByte](./tobyte/)(const char_t *) | 将包含数字字符串表示的 C 字符串转换为等效的 8 位无符号整数值。 |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&) | 将包含数字字符串表示的字符串转换为等效的 8 位无符号整数值。 |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, int) | 将包含指定基数下数字字符串表示的字符串转换为等效的 8 位无符号整数值。 |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息，将包含数字字符串表示的字符串转换为等效的 8 位无符号整数值。 |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息和数字样式，将包含数字字符串表示的字符串转换为等效的 8 位无符号整数值。 |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)([Enum](../enum/)) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 将指定的装箱值转换为等效的 8 位无符号整数值。 |
| static char_t [ToChar](./tochar/)(**bool**) | 不支持转换。始终抛出 InvalidCastException。 |
| static constexpr char_t [ToChar](./tochar/)(**uint8_t**) | 将指定的 8 位无符号整数转换为等效的 Unicode 字符。 |
| static char_t [ToChar](./tochar/)(**int8_t**) | 将指定的 8 位有符号整数转换为等效的 Unicode 字符。 |
| static constexpr char_t [ToChar](./tochar/)(**uint16_t**) | 将指定的 16 位无符号整数转换为等效的 Unicode 字符。 |
| static char_t [ToChar](./tochar/)(**int16_t**) | 将指定的 16 位有符号整数转换为等效的 Unicode 字符。 |
| static char_t [ToChar](./tochar/)(**uint32_t**) | 将指定的 32 位无符号整数转换为等效的 Unicode 字符。 |
| static char_t [ToChar](./tochar/)(**int32_t**) | 将指定的 32 位有符号整数转换为等效的 Unicode 字符。 |
| static char_t [ToChar](./tochar/)(**uint64_t**) | 将指定的 64 位无符号整数转换为等效的 Unicode 字符。 |
| static char_t [ToChar](./tochar/)(**int64_t**) | 将指定的 64 位有符号整数转换为等效的 Unicode 字符。 |
| static char_t [ToChar](./tochar/)(**float**) | 不支持转换。始终抛出 InvalidCastException。 |
| static char_t [ToChar](./tochar/)(**double**) | 不支持转换。始终抛出 InvalidCastException。 |
| static char_t [ToChar](./tochar/)(const [Decimal](../decimal/)\&) | 不支持转换。始终抛出 InvalidCastException。 |
| static constexpr char_t [ToChar](./tochar/)(char_t) | 返回指定的 Unicode 字符。 |
| static char_t [ToChar](./tochar/)([DateTime](../datetime/)) | 不支持转换。始终抛出 InvalidCastException。 |
| static char_t [ToChar](./tochar/)(const char_t *) | 将指定的 C 字符串的首字符（且仅有的字符）转换为 char_t 值。 |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&) | 将指定字符串的首字符（且仅有的字符）转换为 char_t 值。 |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 将指定字符串的首字符（且仅有的字符）转换为 char_t 值。 |
| static char_t [ToChar](./tochar/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 将指定的装箱值转换为等效的 Unicode 字符。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**bool**) | 不支持转换。始终抛出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint8_t**) | 不支持转换。始终抛出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int8_t**) | 不支持转换。始终抛出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint16_t**) | 不支持转换。始终抛出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int16_t**) | 不支持转换。始终抛出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint32_t**) | 不支持转换。始终抛出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int32_t**) | 不支持转换。始终抛出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint64_t**) | 不支持转换。始终抛出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int64_t**) | 不支持转换。始终抛出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**float**) | 不支持转换。始终抛出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**double**) | 不支持转换。始终抛出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [Decimal](../decimal/)\&) | 不支持转换。始终抛出 InvalidCastException。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(char_t) | 不支持转换。始终抛出 InvalidCastException。 |
| static constexpr [DateTime](../datetime/) [ToDateTime](./todatetime/)([DateTime](../datetime/)) | 返回指定的日期和时间。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&) | 将指定字符串转换为 [DateTime](../datetime/) 类的实例。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息，将指定字符串转换为 [DateTime](../datetime/) 类的实例。 |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 将指定的装箱值转换为等效的 [DateTime](../datetime/) 值。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**bool**) | 将指定的布尔值转换为等效的十进制数。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint8_t**) | 将指定的 8 位无符号整数转换为等效的十进制数。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int8_t**) | 将指定的 8 位有符号整数转换为等效的十进制数。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint16_t**) | 将指定的 16 位无符号整数转换为等效的十进制数。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int16_t**) | 将指定的 16 位有符号整数转换为等效的十进制数。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint32_t**) | 将指定的 32 位无符号整数转换为等效的十进制数。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int32_t**) | 将指定的 32 位有符号整数转换为等效的十进制数。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint64_t**) | 将指定的 64 位无符号整数转换为等效的十进制数。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int64_t**) | 将指定的 64 位有符号整数转换为等效的十进制数。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**float**) | 将指定的浮点数转换为等效的十进制数。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**double**) | 将指定的双精度数转换为等效的十进制数。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [Decimal](../decimal/)\&) | 返回指定的十进制数。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(char_t) | 不支持转换。始终抛出 InvalidCastException。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)([DateTime](../datetime/)) | 不支持转换。始终抛出 InvalidCastException。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(std::nullptr_t) | 将指定的空字符串转换为等效的 [Decimal](../decimal/) 值。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const char_t *) | 将包含数字字符串表示的 C 字符串转换为等效的 [Decimal](../decimal/) 值。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&) | 将包含数字字符串表示的字符串转换为等效的 [Decimal](../decimal/) 值。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息，将包含数字字符串表示的字符串转换为等效的 [Decimal](../decimal/) 值。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的数字样式和格式信息，将包含数字字符串表示的字符串转换为等效的 [Decimal](../decimal/) 值。 |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 将指定的装箱值转换为等效的 [Decimal](../decimal/) 值。 |
| static constexpr **double** [ToDouble](./todouble/)(**bool**) | 将指定的布尔值转换为等效的双精度浮点数。 |
| static constexpr **double** [ToDouble](./todouble/)(**uint8_t**) | 将指定的 8 位无符号整数转换为等效的双精度浮点数。 |
| static constexpr **double** [ToDouble](./todouble/)(**int8_t**) | 将指定的 8 位有符号整数转换为等效的双精度浮点数。 |
| static constexpr **double** [ToDouble](./todouble/)(**uint16_t**) | 将指定的 16 位无符号整数转换为等效的双精度浮点数。 |
| static constexpr **double** [ToDouble](./todouble/)(**int16_t**) | 将指定的 16 位有符号整数转换为等效的双精度浮点数。 |
| static constexpr **double** [ToDouble](./todouble/)(**uint32_t**) | 将指定的 32 位无符号整数转换为等效的双精度浮点数。 |
| static constexpr **double** [ToDouble](./todouble/)(**int32_t**) | 将指定的 32 位有符号整数转换为等效的双精度浮点数。 |
| static constexpr **double** [ToDouble](./todouble/)(**uint64_t**) | 将指定的 64 位无符号整数转换为等效的双精度浮点数。 |
| static constexpr **double** [ToDouble](./todouble/)(**int64_t**) | 将指定的 64 位有符号整数转换为等效的双精度浮点数。 |
| static constexpr **double** [ToDouble](./todouble/)(**float**) | 将指定的单精度数转换为等效的双精度浮点数。 |
| static constexpr **double** [ToDouble](./todouble/)(**double**) | 返回指定的双精度数。 |
| static **double** [ToDouble](./todouble/)(const [Decimal](../decimal/)\&) | 将指定的十进制数转换为等效的双精度浮点数。 |
| static **double** [ToDouble](./todouble/)(char_t) | 不支持转换。始终抛出 InvalidCastException。 |
| static **double** [ToDouble](./todouble/)([DateTime](../datetime/)) | 不支持转换。始终抛出 InvalidCastException。 |
| static constexpr **double** [ToDouble](./todouble/)(std::nullptr_t) | 将指定的空字符串转换为等效的双精度浮点值。 |
| static **double** [ToDouble](./todouble/)(const char_t *) | 将包含数字字符串表示的 C 字符串转换为等效的双精度浮点值。 |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&) | 将包含数字字符串表示的字符串转换为等效的双精度浮点值。 |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息，将包含数字字符串表示的字符串转换为等效的双精度浮点值。 |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息和数字样式，将包含数字字符串表示的字符串转换为等效的双精度浮点值。 |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 将指定的装箱值转换为双精度浮点值。如果装箱值的类型为 [String](../string/)，则在转换期间使用指定的字符串格式。 |
| static constexpr **int16_t** [ToInt16](./toint16/)(**bool**) | 将指定的布尔值转换为等效的 16 位有符号整数。 |
| static constexpr **int16_t** [ToInt16](./toint16/)(**uint8_t**) | 将指定的 8 位无符号整数转换为等效的 16 位有符号整数。 |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int8_t**) | 将指定的 8 位有符号整数转换为等效的 16 位有符号整数。 |
| static **int16_t** [ToInt16](./toint16/)(**uint16_t**) | 将指定的 16 位无符号整数转换为等效的 16 位有符号整数。 |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int16_t**) | 返回指定的 16 位有符号整数。 |
| static **int16_t** [ToInt16](./toint16/)(**uint32_t**) | 将指定的 32 位无符号整数转换为等效的 16 位有符号整数。 |
| static **int16_t** [ToInt16](./toint16/)(**int32_t**) | 将指定的 32 位有符号整数转换为等效的 16 位有符号整数。 |
| static **int16_t** [ToInt16](./toint16/)(**uint64_t**) | 将指定的 64 位无符号整数转换为等效的 16 位有符号整数。 |
| static **int16_t** [ToInt16](./toint16/)(**int64_t**) | 将指定的 64 位有符号整数转换为等效的 16 位有符号整数。 |
| static **int16_t** [ToInt16](./toint16/)(**float**) | 将指定的浮点数转换为等效的 16 位有符号整数。 |
| static **int16_t** [ToInt16](./toint16/)(**double**) | 将指定的双精度数转换为等效的 16 位有符号整数。 |
| static **int16_t** [ToInt16](./toint16/)(const [Decimal](../decimal/)\&) | 将指定的十进制数转换为等效的 16 位有符号整数。 |
| static **int16_t** [ToInt16](./toint16/)(char_t) | 将指定的 Unicode 字符转换为等效的 16 位有符号整数。 |
| static **int16_t** [ToInt16](./toint16/)([DateTime](../datetime/)) | 不支持转换。始终抛出 InvalidCastException。 |
| static constexpr **int16_t** [ToInt16](./toint16/)(std::nullptr_t) | 将指定的空字符串转换为等效的 16 位整数值。 |
| static **int16_t** [ToInt16](./toint16/)(const char_t *) | 将包含数字字符串表示的 C 字符串转换为等效的 16 位整数值。 |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&) | 将包含数字字符串表示的字符串转换为等效的 16 位整数值。 |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, int) | 将包含指定基数下数字字符串表示的字符串转换为等效的 16 位整数值。 |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息，将包含数字字符串表示的字符串转换为等效的 16 位整数值。 |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息和数字样式，将包含数字字符串表示的字符串转换为等效的 16 位整数值。 |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)([Enum](../enum/)) |  |
| static **int16_t** [ToInt16](./toint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 将指定的装箱值转换为等效的 16 位整数值。 |
| static constexpr int [ToInt32](./toint32/)(**bool**) | 将指定的布尔值转换为等效的 32 位有符号整数。 |
| static constexpr int [ToInt32](./toint32/)(**uint8_t**) | 将指定的 8 位无符号整数转换为等效的 32 位有符号整数。 |
| static constexpr int [ToInt32](./toint32/)(**int8_t**) | 将指定的 8 位有符号整数转换为等效的 32 位有符号整数。 |
| static constexpr int [ToInt32](./toint32/)(**uint16_t**) | 将指定的 16 位无符号整数转换为等效的 32 位有符号整数。 |
| static constexpr int [ToInt32](./toint32/)(**int16_t**) | 将指定的 16 位有符号整数转换为等效的 32 位有符号整数。 |
| static int [ToInt32](./toint32/)(**uint32_t**) | 将指定的 32 位无符号整数转换为等效的 32 位有符号整数。 |
| static constexpr int [ToInt32](./toint32/)(**int32_t**) | 返回指定的 32 位有符号整数。 |
| static int [ToInt32](./toint32/)(**uint64_t**) | 将指定的 64 位无符号整数转换为等效的 32 位有符号整数。 |
| static int [ToInt32](./toint32/)(**int64_t**) | 将指定的 64 位有符号整数转换为等效的 32 位有符号整数。 |
| static int [ToInt32](./toint32/)(**float**) | 将指定的浮点数转换为等效的 32 位有符号整数。 |
| static int [ToInt32](./toint32/)(**double**) | 将指定的双精度数转换为等效的 32 位有符号整数。 |
| static int [ToInt32](./toint32/)(const [Decimal](../decimal/)\&) | 将指定的十进制数转换为等效的 32 位有符号整数。 |
| static constexpr int [ToInt32](./toint32/)(char_t) | 将指定的 Unicode 字符转换为等效的 32 位有符号整数。 |
| static int [ToInt32](./toint32/)([DateTime](../datetime/)) | 不支持转换。始终抛出 InvalidCastException。 |
| static constexpr int [ToInt32](./toint32/)(std::nullptr_t) | 将指定的空字符串转换为等效的 32 位整数值。 |
| static int [ToInt32](./toint32/)(const char_t *) | 将包含数字字符串表示的 C 字符串转换为等效的 32 位整数值。 |
| static int [ToInt32](./toint32/)(const [String](../string/)\&) | 将包含数字字符串表示的字符串转换为等效的 32 位整数值。 |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, int) | 将包含指定基数下数字字符串表示的字符串转换为等效的 32 位整数值。 |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息，将包含数字字符串表示的字符串转换为等效的 32 位整数值。 |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息和数字样式，将包含数字字符串表示的字符串转换为等效的 32 位整数值。 |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [ToInt32](./toint32/)([Enum](../enum/)) |  |
| static int [ToInt32](./toint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 将指定的装箱值转换为等效的 32 位整数值。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**bool**) | 将指定的布尔值转换为等效的 64 位有符号整数。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint8_t**) | 将指定的 8 位无符号整数转换为等效的 64 位有符号整数。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int8_t**) | 将指定的 8 位有符号整数转换为等效的 64 位有符号整数。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint16_t**) | 将指定的 16 位无符号整数转换为等效的 64 位有符号整数。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int16_t**) | 将指定的 16 位有符号整数转换为等效的 64 位有符号整数。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint32_t**) | 将指定的 32 位无符号整数转换为等效的 64 位有符号整数。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int32_t**) | 将指定的 32 位有符号整数转换为等效的 64 位有符号整数。 |
| static **int64_t** [ToInt64](./toint64/)(**uint64_t**) | 将指定的 64 位无符号整数转换为等效的 64 位有符号整数。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int64_t**) | 返回指定的 64 位有符号整数。 |
| static **int64_t** [ToInt64](./toint64/)(**float**) | 将指定的浮点数转换为等效的 64 位有符号整数。 |
| static **int64_t** [ToInt64](./toint64/)(**double**) | 将指定的双精度数转换为等效的 64 位有符号整数。 |
| static **int64_t** [ToInt64](./toint64/)(const [Decimal](../decimal/)\&) | 将指定的十进制数转换为等效的 64 位有符号整数。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(char_t) | 将指定的 Unicode 字符转换为等效的 64 位有符号整数。 |
| static **int64_t** [ToInt64](./toint64/)([DateTime](../datetime/)) | 不支持转换。始终抛出 InvalidCastException。 |
| static constexpr **int64_t** [ToInt64](./toint64/)(std::nullptr_t) | 将指定的空字符串转换为等效的 64 位整数值。 |
| static **int64_t** [ToInt64](./toint64/)(const char_t *) | 将包含数字字符串表示的 C 字符串转换为等效的 64 位整数值。 |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&) | 将包含数字字符串表示的字符串转换为等效的 64 位整数值。 |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, int) | 将包含指定基数下数字字符串表示的字符串转换为等效的 64 位整数值。 |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息，将包含数字字符串表示的字符串转换为等效的 64 位整数值。 |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息和数字样式，将包含数字字符串表示的字符串转换为等效的 64 位整数值。 |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)([Enum](../enum/)) |  |
| static **int64_t** [ToInt64](./toint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 将指定的装箱值转换为等效的 64 位整数值。 |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**bool**) | 将指定的布尔值转换为等效的 8 位有符号整数。 |
| static **int8_t** [ToSByte](./tosbyte/)(**uint8_t**) | 将指定的 8 位无符号整数转换为等效的 8 位有符号整数。 |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**int8_t**) | 返回指定的 8 位有符号整数。 |
| static **int8_t** [ToSByte](./tosbyte/)(**uint16_t**) | 将指定的 16 位无符号整数转换为等效的 8 位有符号整数。 |
| static **int8_t** [ToSByte](./tosbyte/)(**int16_t**) | 将指定的 16 位有符号整数转换为等效的 8 位有符号整数。 |
| static **int8_t** [ToSByte](./tosbyte/)(**uint32_t**) | 将指定的 32 位无符号整数转换为等效的 8 位有符号整数。 |
| static **int8_t** [ToSByte](./tosbyte/)(**int32_t**) | 将指定的 32 位有符号整数转换为等效的 8 位有符号整数。 |
| static **int8_t** [ToSByte](./tosbyte/)(**uint64_t**) | 将指定的 64 位无符号整数转换为等效的 8 位有符号整数。 |
| static **int8_t** [ToSByte](./tosbyte/)(**int64_t**) | 将指定的 64 位有符号整数转换为等效的 8 位有符号整数。 |
| static **int8_t** [ToSByte](./tosbyte/)(**float**) | 将指定的浮点数转换为等效的 8 位有符号整数。 |
| static **int8_t** [ToSByte](./tosbyte/)(**double**) | 将指定的双精度数转换为等效的 8 位有符号整数。 |
| static **int8_t** [ToSByte](./tosbyte/)(const [Decimal](../decimal/)\&) | 将指定的十进制数转换为等效的 8 位有符号整数。 |
| static **int8_t** [ToSByte](./tosbyte/)(char_t) | 将指定的 Unicode 字符转换为等效的 8 位有符号整数。 |
| static **int8_t** [ToSByte](./tosbyte/)([DateTime](../datetime/)) | 不支持转换。始终抛出 InvalidCastException。 |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(std::nullptr_t) | 将指定的空字符串转换为等效的 8 位整数值。 |
| static **int8_t** [ToSByte](./tosbyte/)(const char_t *) | 将包含数字字符串表示的 C 字符串转换为等效的 8 位整数值。 |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&) | 将包含数字字符串表示的字符串转换为等效的 8 位整数值。 |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, int) | 将包含指定基数下数字字符串表示的字符串转换为等效的 8 位整数值。 |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息，将包含数字字符串表示的字符串转换为等效的无符号 8 位整数值。 |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息和数字样式，将包含数字字符串表示的字符串转换为等效的 8 位整数值。 |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)([Enum](../enum/)) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 将指定的装箱值转换为等效的 8 位整数值。 |
| static constexpr **float** [ToSingle](./tosingle/)(**bool**) | 将指定的布尔值转换为等效的单精度浮点数。 |
| static constexpr **float** [ToSingle](./tosingle/)(**uint8_t**) | 将指定的 8 位无符号整数转换为等效的单精度浮点数。 |
| static constexpr **float** [ToSingle](./tosingle/)(**int8_t**) | 将指定的 8 位有符号整数转换为等效的单精度浮点数。 |
| static constexpr **float** [ToSingle](./tosingle/)(**uint16_t**) | 将指定的 16 位无符号整数转换为等效的单精度浮点数。 |
| static constexpr **float** [ToSingle](./tosingle/)(**int16_t**) | 将指定的 16 位有符号整数转换为等效的单精度浮点数。 |
| static constexpr **float** [ToSingle](./tosingle/)(**uint32_t**) | 将指定的 32 位无符号整数转换为等效的单精度浮点数。 |
| static constexpr **float** [ToSingle](./tosingle/)(**int32_t**) | 将指定的 32 位有符号整数转换为等效的单精度浮点数。 |
| static constexpr **float** [ToSingle](./tosingle/)(**uint64_t**) | 将指定的 64 位无符号整数转换为等效的单精度浮点数。 |
| static constexpr **float** [ToSingle](./tosingle/)(**int64_t**) | 将指定的 64 位有符号整数转换为等效的单精度浮点数。 |
| static constexpr **float** [ToSingle](./tosingle/)(**float**) | 返回指定的浮点数。 |
| static constexpr **float** [ToSingle](./tosingle/)(**double**) | 将指定的双精度数转换为等效的单精度浮点数。 |
| static **float** [ToSingle](./tosingle/)(const [Decimal](../decimal/)\&) | 将指定的十进制数转换为等效的单精度浮点数。 |
| static **float** [ToSingle](./tosingle/)(char_t) | 不支持转换。始终抛出 InvalidCastException。 |
| static **float** [ToSingle](./tosingle/)([DateTime](../datetime/)) | 不支持转换。始终抛出 InvalidCastException。 |
| static constexpr **float** [ToSingle](./tosingle/)(std::nullptr_t) | 将指定的空字符串转换为等效的单精度浮点值。 |
| static **float** [ToSingle](./tosingle/)(const char_t *) | 将包含数字字符串表示的 C 字符串转换为等效的单精度浮点值。 |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&) | 将包含数字字符串表示的字符串转换为等效的单精度浮点值。 |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息，将包含数字字符串表示的字符串转换为等效的单精度浮点值。 |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息和数字样式，将包含数字字符串表示的字符串转换为等效的单精度浮点值。 |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 将指定的装箱值转换为单精度浮点值。 |
| static [String](../string/) [ToString](./tostring/)(**int8_t**) | 将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**) | 将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**int16_t**) | 将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**) | 将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**int32_t**) | 将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**) | 将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**int64_t**) | 将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**) | 将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**float**) | 将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**double**) | 将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&) | 将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/)) | 将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用区域特定的格式信息将指定的值转换为字符串。 |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用区域特定的格式信息将指定的值转换为字符串。 |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用区域特定的格式信息将指定的值转换为字符串。 |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用区域特定的格式信息将指定的值转换为字符串。 |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用区域特定的格式信息将指定的值转换为字符串。 |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用区域特定的格式信息将指定的值转换为字符串。 |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用区域特定的格式信息将指定的值转换为字符串。 |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用区域特定的格式信息将指定的值转换为字符串。 |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用区域特定的格式信息将指定的值转换为字符串。 |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用区域特定的格式信息将指定的值转换为字符串。 |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用区域特定的格式信息将指定的值转换为字符串。 |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用区域特定的格式信息将指定的值转换为字符串。 |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的字符串格式和由指定 [IFormatProvider](../iformatprovider/) 对象提供的区域特定格式信息，将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的字符串格式和由指定 [IFormatProvider](../iformatprovider/) 对象提供的区域特定格式信息，将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的字符串格式和由指定 [IFormatProvider](../iformatprovider/) 对象提供的区域特定格式信息，将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的字符串格式和由指定 [IFormatProvider](../iformatprovider/) 对象提供的区域特定格式信息，将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的字符串格式和由指定 [IFormatProvider](../iformatprovider/) 对象提供的区域特定格式信息，将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的字符串格式和由指定 [IFormatProvider](../iformatprovider/) 对象提供的区域特定格式信息，将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的字符串格式和由指定 [IFormatProvider](../iformatprovider/) 对象提供的区域特定格式信息，将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的字符串格式和由指定 [IFormatProvider](../iformatprovider/) 对象提供的区域特定格式信息，将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的字符串格式和由指定 [IFormatProvider](../iformatprovider/) 对象提供的区域特定格式信息，将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的字符串格式和由指定 [IFormatProvider](../iformatprovider/) 对象提供的区域特定格式信息，将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的字符串格式和由指定 [IFormatProvider](../iformatprovider/) 对象提供的区域特定格式信息，将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的字符串格式和由指定 [IFormatProvider](../iformatprovider/) 对象提供的区域特定格式信息，将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&) | 将指定的值转换为字符串。 |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&, const [String](../string/)\&) | 使用指定的字符串格式将指定的值转换为字符串。 |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), std::nullptr_t) | 将指定的 Unicode 字符数组转换为字符串。 |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的区域特定格式信息（由指定 [IFormatProvider](../iformatprovider/) 对象提供），将指定的 Unicode 字符数组转换为字符串。 |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) | 返回指定的值；不执行转换。 |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 返回指定的值；不执行转换。 |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 返回指定的值；不执行转换。 |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | 返回指定的值；不执行转换。 |
| static [String](../string/) [ToString](./tostring/)(char_t, std::nullptr_t) | 返回指定的值；不执行转换。 |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 返回指定的值；不执行转换。 |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 返回指定的值；不执行转换。 |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 返回指定的值；不执行转换。 |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 返回指定的值；不执行转换。 |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, std::nullptr_t) | 返回指定的值；不执行转换。 |
| static [String](../string/) [ToString](./tostring/)(**bool**, std::nullptr_t) | 将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | 将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, std::nullptr_t) | 将指定的值转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, int) | 将指定的整数值以指定的基数转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, int) | 将指定的整数值以指定的基数转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, int) | 将指定的整数值以指定的基数转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, int) | 将指定的整数值以指定的基数转换为其字符串表示形式。 |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 将指定的装箱值转换为其字符串表示形式。如果装箱值的类型为 [String](../string/)，则在转换期间使用指定的字符串格式。 |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**bool**) | 将指定的布尔值转换为等效的 16 位无符号整数。 |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint8_t**) | 将指定的 8 位无符号整数转换为等效的 16 位无符号整数。 |
| static **uint16_t** [ToUInt16](./touint16/)(**int8_t**) | 将指定的 8 位有符号整数转换为等效的 16 位无符号整数。 |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint16_t**) | 返回指定的 16 位无符号整数。 |
| static **uint16_t** [ToUInt16](./touint16/)(**int16_t**) | 将指定的 16 位有符号整数转换为等效的 16 位无符号整数。 |
| static **uint16_t** [ToUInt16](./touint16/)(**uint32_t**) | 将指定的 32 位无符号整数转换为等效的 16 位无符号整数。 |
| static **uint16_t** [ToUInt16](./touint16/)(**int32_t**) | 将指定的 32 位有符号整数转换为等效的 16 位无符号整数。 |
| static **uint16_t** [ToUInt16](./touint16/)(**uint64_t**) | 将指定的 64 位无符号整数转换为等效的 16 位无符号整数。 |
| static **uint16_t** [ToUInt16](./touint16/)(**int64_t**) | 将指定的 64 位有符号整数转换为等效的 16 位无符号整数。 |
| static **uint16_t** [ToUInt16](./touint16/)(**float**) | 将指定的浮点数转换为等效的 16 位无符号整数。 |
| static **uint16_t** [ToUInt16](./touint16/)(**double**) | 将指定的双精度数转换为等效的 16 位无符号整数。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [Decimal](../decimal/)\&) | 将指定的十进制数转换为等效的 16 位无符号整数。 |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(char_t) | 将指定的 Unicode 字符转换为等效的 16 位无符号整数。 |
| static **uint16_t** [ToUInt16](./touint16/)([DateTime](../datetime/)) | 不支持转换。始终抛出 InvalidCastException。 |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(std::nullptr_t) | 将指定的空字符串转换为等效的无符号 16 位整数值。 |
| static **uint16_t** [ToUInt16](./touint16/)(const char_t *) | 将包含数字字符串表示的 C 字符串转换为等效的无符号 16 位整数值。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&) | 将包含数字字符串表示的字符串转换为等效的无符号 16 位整数值。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, int) | 将包含指定基数下数字字符串表示的字符串转换为等效的无符号 16 位整数值。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息，将包含数字字符串表示的字符串转换为等效的无符号 16 位整数值。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息和数字样式，将包含数字字符串表示的字符串转换为等效的无符号 16 位整数值。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)([Enum](../enum/)) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 将指定的装箱值转换为等效的无符号 16 位整数值。 |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**bool**) | 将指定的布尔值转换为等效的 32 位无符号整数。 |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint8_t**) | 将指定的 8 位无符号整数转换为等效的 32 位无符号整数。 |
| static **uint32_t** [ToUInt32](./touint32/)(**int8_t**) | 将指定的 8 位有符号整数转换为等效的 32 位无符号整数。 |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint16_t**) | 将指定的 16 位无符号整数转换为等效的 32 位无符号整数。 |
| static **uint32_t** [ToUInt32](./touint32/)(**int16_t**) | 将指定的 16 位有符号整数转换为等效的 32 位无符号整数。 |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint32_t**) | 返回指定的 32 位无符号整数。 |
| static **uint32_t** [ToUInt32](./touint32/)(**int32_t**) | 将指定的 32 位有符号整数转换为等效的 32 位无符号整数。 |
| static **uint32_t** [ToUInt32](./touint32/)(**uint64_t**) | 将指定的 64 位无符号整数转换为等效的 32 位无符号整数。 |
| static **uint32_t** [ToUInt32](./touint32/)(**int64_t**) | 将指定的 64 位有符号整数转换为等效的 32 位无符号整数。 |
| static **uint32_t** [ToUInt32](./touint32/)(**float**) | 将指定的浮点数转换为等效的 32 位无符号整数。 |
| static **uint32_t** [ToUInt32](./touint32/)(**double**) | 将指定的双精度数转换为等效的 32 位无符号整数。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [Decimal](../decimal/)\&) | 将指定的十进制数转换为等效的 32 位无符号整数。 |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(char_t) | 将指定的 Unicode 字符转换为等效的 32 位无符号整数。 |
| static **uint32_t** [ToUInt32](./touint32/)([DateTime](../datetime/)) | 不支持转换。始终抛出 InvalidCastException。 |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(std::nullptr_t) | 将指定的空字符串转换为等效的无符号 32 位整数值。 |
| static **uint32_t** [ToUInt32](./touint32/)(const char_t *) | 将包含数字字符串表示的 C 字符串转换为等效的无符号 32 位整数值。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&) | 将包含数字字符串表示的字符串转换为等效的无符号 32 位整数值。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, int) | 将包含指定基数下数字字符串表示的字符串转换为等效的无符号 32 位整数值。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息，将包含数字字符串表示的字符串转换为等效的无符号 32 位整数值。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息和数字样式，将包含数字字符串表示的字符串转换为等效的无符号 32 位整数值。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)([Enum](../enum/)) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 将指定的装箱值转换为等效的无符号 32 位整数值。 |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**bool**) | 将指定的布尔值转换为等效的 64 位无符号整数。 |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint8_t**) | 将指定的 8 位无符号整数转换为等效的 64 位无符号整数。 |
| static **uint64_t** [ToUInt64](./touint64/)(**int8_t**) | 将指定的 8 位有符号整数转换为等效的 64 位无符号整数。 |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint16_t**) | 将指定的 16 位无符号整数转换为等效的 64 位无符号整数。 |
| static **uint64_t** [ToUInt64](./touint64/)(**int16_t**) | 将指定的 16 位有符号整数转换为等效的 64 位无符号整数。 |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint32_t**) | 将指定的 32 位无符号整数转换为等效的 64 位无符号整数。 |
| static **uint64_t** [ToUInt64](./touint64/)(**int32_t**) | 将指定的 32 位有符号整数转换为等效的 64 位无符号整数。 |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint64_t**) | 返回指定的 64 位无符号整数。 |
| static **uint64_t** [ToUInt64](./touint64/)(**int64_t**) | 将指定的 64 位有符号整数转换为等效的 64 位无符号整数。 |
| static **uint64_t** [ToUInt64](./touint64/)(**float**) | 将指定的浮点数转换为等效的 64 位无符号整数。 |
| static **uint64_t** [ToUInt64](./touint64/)(**double**) | 将指定的双精度数转换为等效的 64 位无符号整数。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [Decimal](../decimal/)\&) | 将指定的十进制数转换为等效的 64 位无符号整数。 |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(char_t) | 将指定的 Unicode 字符转换为等效的 64 位无符号整数。 |
| static **uint64_t** [ToUInt64](./touint64/)([DateTime](../datetime/)) | 不支持转换。始终抛出 InvalidCastException。 |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(std::nullptr_t) | 将指定的空字符串转换为等效的无符号 64 位整数值。 |
| static **uint64_t** [ToUInt64](./touint64/)(const char_t *) | 将包含数字字符串表示的 C 字符串转换为等效的无符号 64 位整数值。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&) | 将包含数字字符串表示的字符串转换为等效的无符号 64 位整数值。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, int) | 将包含指定基数下数字字符串表示的字符串转换为等效的无符号 64 位整数值。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息，将包含数字字符串表示的字符串转换为等效的无符号 64 位整数值。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式信息和数字样式，将包含数字字符串表示的字符串转换为等效的无符号 64 位整数值。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)([Enum](../enum/)) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 将指定的装箱值转换为等效的无符号 64 位整数值。 |
## 参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)