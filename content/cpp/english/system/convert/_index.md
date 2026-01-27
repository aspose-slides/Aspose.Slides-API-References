---
title: Convert
second_title: Aspose.Slides for C++ API Reference
description: "The structure that contains methods performing conversion of values of one type to the values of another type. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type."
type: docs
weight: 1522
url: /system/convert/
---
## Convert struct


The structure that contains methods performing conversion of values of one type to the values of another type. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class Convert
```

## Methods

| Method | Description |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&) | NOT IMPLEMENTED. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64CharArray](./frombase64chararray/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Decodes base-64 encoded data represented as a range in the array of Unicode characters. |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64String](./frombase64string/)(const [String](../string/)\&) | Decodes base-64 encoded data represented as a string. |
| static [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Returns a TypeCode value representing the type of the specified boxed value. |
| static std::enable_if_t<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\> [IsDBNull](./isdbnull/)(const T\&) | NOT IMPLEMENTED. |
| static **bool** [IsDBNull](./isdbnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | NOT IMPLEMENTED Fake implementation, checks if value is nullptr. |
| static Target [To](./to/)(const Source\&) |  |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, **bool**) | Base-64 encodes a range of elements in the specified byte array and stores the encoded data as an array of Unicode characters. |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, [Base64FormattingOptions](../base64formattingoptions/)) | Base-64 encodes a range of elements in the specified byte array and stores the encoded data as an array of Unicode characters. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**) | Base-64 encodes elements in the specified byte array and returns the encoded data as a string. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, **bool**) | Base-64 encodes a range of elements in the specified byte array and returns the encoded data as a string. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, [Base64FormattingOptions](../base64formattingoptions/)) | Base-64 encodes elements in the specified byte array and returns the encoded data as a string. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, [Base64FormattingOptions](../base64formattingoptions/)) | Base-64 encodes a range of elements in the specified byte array and returns the encoded data as a string. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**bool**) | Returns the specified boolean value. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint8_t**) | Converts the specified 8-bit unsigned integer to an equivalent boolean value. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int8_t**) | Converts the specified 8-bit signed integer to an equivalent boolean value. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint16_t**) | Converts the specified 16-bit unsigned integer to an equivalent boolean value. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int16_t**) | Converts the specified 16-bit signed integer to an equivalent boolean value. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint32_t**) | Converts the specified 32-bit unsigned integer to an equivalent boolean value. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int32_t**) | Converts the specified 32-bit signed integer to an equivalent boolean value. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint64_t**) | Converts the specified 64-bit unsigned integer to an equivalent boolean value. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int64_t**) | Converts the specified 64-bit signed integer to an equivalent boolean value. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**float**) | Converts the specified float number to an equivalent boolean value. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**double**) | Converts the specified double number to an equivalent boolean value. |
| static **bool** [ToBoolean](./toboolean/)(const [Decimal](../decimal/)\&) | Converts the specified decimal number to an equivalent boolean value. |
| static **bool** [ToBoolean](./toboolean/)(char_t) | Conversion is not supported. Always throws InvalidCastException. |
| static **bool** [ToBoolean](./toboolean/)([DateTime](../datetime/)) | Conversion is not supported. Always throws InvalidCastException. |
| static constexpr **bool** [ToBoolean](./toboolean/)(std::nullptr_t) | Converts the specified null-string to the equivalent boolean value. |
| static **bool** [ToBoolean](./toboolean/)(const char_t *) | Converts the specified c-string to the value of bool type. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&) | Converts the specified string to the value of bool type. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string to the value of bool type. |
| static **bool** [ToBoolean](./toboolean/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified boxed value to equivalent boolean value. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**bool**) | Converts the specified boolean value to an equivalent 8-bit unsigned integer. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**uint8_t**) | Returns the specified 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)(**int8_t**) | Converts the specified 8-bit signed integer to an equivalent 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)(**uint16_t**) | Converts the specified 16-bit unsigned integer to an equivalent 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)(**int16_t**) | Converts the specified 16-bit signed integer to an equivalent 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)(**uint32_t**) | Converts the specified 32-bit unsigned integer to an equivalent 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)(**int32_t**) | Converts the specified 32-bit signed integer to an equivalent 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)(**uint64_t**) | Converts the specified 64-bit unsigned integer to an equivalent 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)(**int64_t**) | Converts the specified 64-bit signed integer to an equivalent 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)(**float**) | Converts the specified float number to an equivalent 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)(**double**) | Converts the specified double number to an equivalent 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)(const [Decimal](../decimal/)\&) | Converts the specified decimal number to an equivalent 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)(char_t) | Converts the specified unicode character to an equivalent 8-bit unsigned integer. |
| static **uint8_t** [ToByte](./tobyte/)([DateTime](../datetime/)) | Conversion is not supported. Always throws InvalidCastException. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(std::nullptr_t) | Converts the specified null-string to the equivalent unsigned 8-bit integer value. |
| static **uint8_t** [ToByte](./tobyte/)(const char_t *) | Converts the specified c-string containing the string representation of a number to the equivalent unsigned 8-bit integer value. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&) | Converts the specified string containing the string representation of a number to the equivalent unsigned 8-bit integer value. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, int) | Converts the specified string containing the string representation of a number in the specified base to the equivalent unsigned 8-bit integer value. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent unsigned 8-bit integer value using the provided formatting information. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent unsigned 8-bit integer value using the provided formatting information and number style. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)([Enum](../enum/)) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified boxed value to equivalent unsigned 8-bit integer value. |
| static char_t [ToChar](./tochar/)(**bool**) | Conversion is not supported. Always throws InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(**uint8_t**) | Converts the specified 8-bit unsigned integer to an equivalent unicode character. |
| static char_t [ToChar](./tochar/)(**int8_t**) | Converts the specified 8-bit signed integer to an equivalent unicode character. |
| static constexpr char_t [ToChar](./tochar/)(**uint16_t**) | Converts the specified 16-bit unsigned integer to an equivalent unicode character. |
| static char_t [ToChar](./tochar/)(**int16_t**) | Converts the specified 16-bit signed integer to an equivalent unicode character. |
| static char_t [ToChar](./tochar/)(**uint32_t**) | Converts the specified 32-bit unsigned integer to an equivalent unicode character. |
| static char_t [ToChar](./tochar/)(**int32_t**) | Converts the specified 32-bit signed integer to an equivalent unicode character. |
| static char_t [ToChar](./tochar/)(**uint64_t**) | Converts the specified 64-bit unsigned integer to an equivalent unicode character. |
| static char_t [ToChar](./tochar/)(**int64_t**) | Converts the specified 64-bit signed integer to an equivalent unicode character. |
| static char_t [ToChar](./tochar/)(**float**) | Conversion is not supported. Always throws InvalidCastException. |
| static char_t [ToChar](./tochar/)(**double**) | Conversion is not supported. Always throws InvalidCastException. |
| static char_t [ToChar](./tochar/)(const [Decimal](../decimal/)\&) | Conversion is not supported. Always throws InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(char_t) | Returns the specified unicode character. |
| static char_t [ToChar](./tochar/)([DateTime](../datetime/)) | Conversion is not supported. Always throws InvalidCastException. |
| static char_t [ToChar](./tochar/)(const char_t *) | Converts the first and the only character of the specified c-string to a char_t value. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&) | Converts the first and the only character of the specified string to a char_t value. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the first and the only character of the specified string to a char_t value. |
| static char_t [ToChar](./tochar/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified boxed value to equivalent unicode character. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**bool**) | Conversion is not supported. Always throws InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint8_t**) | Conversion is not supported. Always throws InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int8_t**) | Conversion is not supported. Always throws InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint16_t**) | Conversion is not supported. Always throws InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int16_t**) | Conversion is not supported. Always throws InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint32_t**) | Conversion is not supported. Always throws InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int32_t**) | Conversion is not supported. Always throws InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint64_t**) | Conversion is not supported. Always throws InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int64_t**) | Conversion is not supported. Always throws InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**float**) | Conversion is not supported. Always throws InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**double**) | Conversion is not supported. Always throws InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [Decimal](../decimal/)\&) | Conversion is not supported. Always throws InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(char_t) | Conversion is not supported. Always throws InvalidCastException. |
| static constexpr [DateTime](../datetime/) [ToDateTime](./todatetime/)([DateTime](../datetime/)) | Returns the specified date and time. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&) | Converts the specified string to an instance of [DateTime](../datetime/) class. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string to an instance of [DateTime](../datetime/) class using the provided formatting information. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified boxed value to equivalent [DateTime](../datetime/) value. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**bool**) | Converts the specified boolean value to an equivalent decimal number. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint8_t**) | Converts the specified 8-bit unsigned integer to an equivalent decimal number. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int8_t**) | Converts the specified 8-bit signed integer to an equivalent decimal number. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint16_t**) | Converts the specified 16-bit unsigned integer to an equivalent decimal number. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int16_t**) | Converts the specified 16-bit signed integer to an equivalent decimal number. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint32_t**) | Converts the specified 32-bit unsigned integer to an equivalent decimal number. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int32_t**) | Converts the specified 32-bit signed integer to an equivalent decimal number. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint64_t**) | Converts the specified 64-bit unsigned integer to an equivalent decimal number. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int64_t**) | Converts the specified 64-bit signed integer to an equivalent decimal number. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**float**) | Converts the specified float number to an equivalent decimal number. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**double**) | Converts the specified double number to an equivalent decimal number. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [Decimal](../decimal/)\&) | Returns the specified decimal number. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(char_t) | Conversion is not supported. Always throws InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)([DateTime](../datetime/)) | Conversion is not supported. Always throws InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(std::nullptr_t) | Converts the specified null-string to the equivalent [Decimal](../decimal/) value. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const char_t *) | Converts the specified c-string containing the string representation of a number to the equivalent [Decimal](../decimal/) value. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&) | Converts the specified string containing the string representation of a number to the equivalent [Decimal](../decimal/) value. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent [Decimal](../decimal/) value using the provided formatting information. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent [Decimal](../decimal/) value using the specified number styles and formatting information. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified boxed value to equivalent [Decimal](../decimal/) value. |
| static constexpr **double** [ToDouble](./todouble/)(**bool**) | Converts the specified boolean value to an equivalent double-precision floating-point number. |
| static constexpr **double** [ToDouble](./todouble/)(**uint8_t**) | Converts the specified 8-bit unsigned integer to an equivalent double-precision floating-point number. |
| static constexpr **double** [ToDouble](./todouble/)(**int8_t**) | Converts the specified 8-bit signed integer to an equivalent double-precision floating-point number. |
| static constexpr **double** [ToDouble](./todouble/)(**uint16_t**) | Converts the specified 16-bit unsigned integer to an equivalent double-precision floating-point number. |
| static constexpr **double** [ToDouble](./todouble/)(**int16_t**) | Converts the specified 16-bit signed integer to an equivalent double-precision floating-point number. |
| static constexpr **double** [ToDouble](./todouble/)(**uint32_t**) | Converts the specified 32-bit unsigned integer to an equivalent double-precision floating-point number. |
| static constexpr **double** [ToDouble](./todouble/)(**int32_t**) | Converts the specified 32-bit signed integer to an equivalent double-precision floating-point number. |
| static constexpr **double** [ToDouble](./todouble/)(**uint64_t**) | Converts the specified 64-bit unsigned integer to an equivalent double-precision floating-point number. |
| static constexpr **double** [ToDouble](./todouble/)(**int64_t**) | Converts the specified 64-bit signed integer to an equivalent double-precision floating-point number. |
| static constexpr **double** [ToDouble](./todouble/)(**float**) | Converts the specified single-precision number to an equivalent double-precision floating-point number. |
| static constexpr **double** [ToDouble](./todouble/)(**double**) | Returns the specified double number. |
| static **double** [ToDouble](./todouble/)(const [Decimal](../decimal/)\&) | Converts the specified decimal number to an equivalent double-precision floating-point number. |
| static **double** [ToDouble](./todouble/)(char_t) | Conversion is not supported. Always throws InvalidCastException. |
| static **double** [ToDouble](./todouble/)([DateTime](../datetime/)) | Conversion is not supported. Always throws InvalidCastException. |
| static constexpr **double** [ToDouble](./todouble/)(std::nullptr_t) | Converts the specified null-string to the equivalent double-precision floating-point value. |
| static **double** [ToDouble](./todouble/)(const char_t *) | Converts the specified c-string containing the string representation of a number to the equivalent double-precision floating-point value. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&) | Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value using the provided formatting information. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value using the provided formatting information and number style. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified boxed value to double-precision floating-point value. If the type of boxed value is [String](../string/), the specified string format is used during conversion. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**bool**) | Converts the specified boolean value to an equivalent 16-bit signed integer. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**uint8_t**) | Converts the specified 8-bit unsigned integer to an equivalent 16-bit signed integer. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int8_t**) | Converts the specified 8-bit signed integer to an equivalent 16-bit signed integer. |
| static **int16_t** [ToInt16](./toint16/)(**uint16_t**) | Converts the specified 16-bit unsigned integer to an equivalent 16-bit signed integer. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int16_t**) | Returns the specified 16-bit signed integer. |
| static **int16_t** [ToInt16](./toint16/)(**uint32_t**) | Converts the specified 32-bit unsigned integer to an equivalent 16-bit signed integer. |
| static **int16_t** [ToInt16](./toint16/)(**int32_t**) | Converts the specified 32-bit signed integer to an equivalent 16-bit signed integer. |
| static **int16_t** [ToInt16](./toint16/)(**uint64_t**) | Converts the specified 64-bit unsigned integer to an equivalent 16-bit signed integer. |
| static **int16_t** [ToInt16](./toint16/)(**int64_t**) | Converts the specified 64-bit signed integer to an equivalent 16-bit signed integer. |
| static **int16_t** [ToInt16](./toint16/)(**float**) | Converts the specified float number to an equivalent 16-bit signed integer. |
| static **int16_t** [ToInt16](./toint16/)(**double**) | Converts the specified double number to an equivalent 16-bit signed integer. |
| static **int16_t** [ToInt16](./toint16/)(const [Decimal](../decimal/)\&) | Converts the specified decimal number to an equivalent 16-bit signed integer. |
| static **int16_t** [ToInt16](./toint16/)(char_t) | Converts the specified unicode character to an equivalent 16-bit signed integer. |
| static **int16_t** [ToInt16](./toint16/)([DateTime](../datetime/)) | Conversion is not supported. Always throws InvalidCastException. |
| static constexpr **int16_t** [ToInt16](./toint16/)(std::nullptr_t) | Converts the specified null-string to the equivalent 16-bit integer value. |
| static **int16_t** [ToInt16](./toint16/)(const char_t *) | Converts the specified c-string containing the string representation of a number to the equivalent 16-bit integer value. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&) | Converts the specified string containing the string representation of a number to the equivalent 16-bit integer value. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, int) | Converts the specified string containing the string representation of a number in the specified base to the equivalent 16-bit integer value. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent 16-bit integer value using the provided formatting information. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent 16-bit integer value using the provided formatting information and number style. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)([Enum](../enum/)) |  |
| static **int16_t** [ToInt16](./toint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified boxed value to equivalent 16-bit integer value. |
| static constexpr int [ToInt32](./toint32/)(**bool**) | Converts the specified boolean value to an equivalent 32-bit signed integer. |
| static constexpr int [ToInt32](./toint32/)(**uint8_t**) | Converts the specified 8-bit unsigned integer to an equivalent 32-bit signed integer. |
| static constexpr int [ToInt32](./toint32/)(**int8_t**) | Converts the specified 8-bit signed integer to an equivalent 32-bit signed integer. |
| static constexpr int [ToInt32](./toint32/)(**uint16_t**) | Converts the specified 16-bit unsigned integer to an equivalent 32-bit signed integer. |
| static constexpr int [ToInt32](./toint32/)(**int16_t**) | Converts the specified 16-bit signed integer to an equivalent 32-bit signed integer. |
| static int [ToInt32](./toint32/)(**uint32_t**) | Converts the specified 32-bit unsigned integer to an equivalent 32-bit signed integer. |
| static constexpr int [ToInt32](./toint32/)(**int32_t**) | Returns the specified 32-bit signed integer. |
| static int [ToInt32](./toint32/)(**uint64_t**) | Converts the specified 64-bit unsigned integer to an equivalent 32-bit signed integer. |
| static int [ToInt32](./toint32/)(**int64_t**) | Converts the specified 64-bit signed integer to an equivalent 32-bit signed integer. |
| static int [ToInt32](./toint32/)(**float**) | Converts the specified float number to an equivalent 32-bit signed integer. |
| static int [ToInt32](./toint32/)(**double**) | Converts the specified double number to an equivalent 32-bit signed integer. |
| static int [ToInt32](./toint32/)(const [Decimal](../decimal/)\&) | Converts the specified decimal number to an equivalent 32-bit signed integer. |
| static constexpr int [ToInt32](./toint32/)(char_t) | Converts the specified unicode character to an equivalent 32-bit signed integer. |
| static int [ToInt32](./toint32/)([DateTime](../datetime/)) | Conversion is not supported. Always throws InvalidCastException. |
| static constexpr int [ToInt32](./toint32/)(std::nullptr_t) | Converts the specified null-string to the equivalent 32-bit integer value. |
| static int [ToInt32](./toint32/)(const char_t *) | Converts the specified c-string containing the string representation of a number to the equivalent 32-bit integer value. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&) | Converts the specified string containing the string representation of a number to the equivalent 32-bit integer value. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, int) | Converts the specified string containing the string representation of a number in the specified base to the equivalent 32-bit integer value. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent 32-bit integer value using the provided formatting information. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent 32-bit integer value using the provided formatting information and number style. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [ToInt32](./toint32/)([Enum](../enum/)) |  |
| static int [ToInt32](./toint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified boxed value to equivalent 32-bit integer value. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**bool**) | Converts the specified boolean value to an equivalent 64-bit signed integer. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint8_t**) | Converts the specified 8-bit unsigned integer to an equivalent 64-bit signed integer. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int8_t**) | Converts the specified 8-bit signed integer to an equivalent 64-bit signed integer. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint16_t**) | Converts the specified 16-bit unsigned integer to an equivalent 64-bit signed integer. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int16_t**) | Converts the specified 16-bit signed integer to an equivalent 64-bit signed integer. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint32_t**) | Converts the specified 32-bit unsigned integer to an equivalent 64-bit signed integer. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int32_t**) | Converts the specified 32-bit signed integer to an equivalent 64-bit signed integer. |
| static **int64_t** [ToInt64](./toint64/)(**uint64_t**) | Converts the specified 64-bit unsigned integer to an equivalent 64-bit signed integer. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int64_t**) | Returns the specified 64-bit signed integer. |
| static **int64_t** [ToInt64](./toint64/)(**float**) | Converts the specified float number to an equivalent 64-bit signed integer. |
| static **int64_t** [ToInt64](./toint64/)(**double**) | Converts the specified double number to an equivalent 64-bit signed integer. |
| static **int64_t** [ToInt64](./toint64/)(const [Decimal](../decimal/)\&) | Converts the specified decimal number to an equivalent 64-bit signed integer. |
| static constexpr **int64_t** [ToInt64](./toint64/)(char_t) | Converts the specified unicode character to an equivalent 64-bit signed integer. |
| static **int64_t** [ToInt64](./toint64/)([DateTime](../datetime/)) | Conversion is not supported. Always throws InvalidCastException. |
| static constexpr **int64_t** [ToInt64](./toint64/)(std::nullptr_t) | Converts the specified null-string to the equivalent int 64-bit integer value. |
| static **int64_t** [ToInt64](./toint64/)(const char_t *) | Converts the specified c-string containing the string representation of a number to the equivalent 64-bit integer value. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&) | Converts the specified string containing the string representation of a number to the equivalent 64-bit integer value. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, int) | Converts the specified string containing the string representation of a number in the specified base to the equivalent 64-bit integer value. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent 64-bit integer value using the provided formatting information. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent 64-bit integer value using the provided formatting information and number style. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)([Enum](../enum/)) |  |
| static **int64_t** [ToInt64](./toint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified boxed value to equivalent 64-bit integer value. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**bool**) | Converts the specified boolean value to an equivalent 8-bit signed integer. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint8_t**) | Converts the specified 8-bit unsigned integer to an equivalent 8-bit signed integer. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**int8_t**) | Returns the specified 8-bit signed integer. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint16_t**) | Converts the specified 16-bit unsigned integer to an equivalent 8-bit signed integer. |
| static **int8_t** [ToSByte](./tosbyte/)(**int16_t**) | Converts the specified 16-bit signed integer to an equivalent 8-bit signed integer. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint32_t**) | Converts the specified 32-bit unsigned integer to an equivalent 8-bit signed integer. |
| static **int8_t** [ToSByte](./tosbyte/)(**int32_t**) | Converts the specified 32-bit signed integer to an equivalent 8-bit signed integer. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint64_t**) | Converts the specified 64-bit unsigned integer to an equivalent 8-bit signed integer. |
| static **int8_t** [ToSByte](./tosbyte/)(**int64_t**) | Converts the specified 64-bit signed integer to an equivalent 8-bit signed integer. |
| static **int8_t** [ToSByte](./tosbyte/)(**float**) | Converts the specified float number to an equivalent 8-bit signed integer. |
| static **int8_t** [ToSByte](./tosbyte/)(**double**) | Converts the specified double number to an equivalent 8-bit signed integer. |
| static **int8_t** [ToSByte](./tosbyte/)(const [Decimal](../decimal/)\&) | Converts the specified decimal number to an equivalent 8-bit signed integer. |
| static **int8_t** [ToSByte](./tosbyte/)(char_t) | Converts the specified unicode character to an equivalent 8-bit signed integer. |
| static **int8_t** [ToSByte](./tosbyte/)([DateTime](../datetime/)) | Conversion is not supported. Always throws InvalidCastException. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(std::nullptr_t) | Converts the specified null-string to the equivalent 8-bit integer value. |
| static **int8_t** [ToSByte](./tosbyte/)(const char_t *) | Converts the specified c-string containing the string representation of a number to the equivalent 8-bit integer value. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&) | Converts the specified string containing the string representation of a number to the equivalent 8-bit integer value. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, int) | Converts the specified string containing the string representation of a number in the specified base to the equivalent 8-bit integer value. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent unsigned 8-bit integer value using the provided formatting information. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent 8-bit integer value using the provided formatting information and number style. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)([Enum](../enum/)) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified boxed value to equivalent 8-bit integer value. |
| static constexpr **float** [ToSingle](./tosingle/)(**bool**) | Converts the specified boolean value to an equivalent single-precision floating-point number. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint8_t**) | Converts the specified 8-bit unsigned integer to an equivalent single-precision floating-point number. |
| static constexpr **float** [ToSingle](./tosingle/)(**int8_t**) | Converts the specified 8-bit signed integer to an equivalent single-precision floating-point number. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint16_t**) | Converts the specified 16-bit unsigned integer to an equivalent single-precision floating-point number. |
| static constexpr **float** [ToSingle](./tosingle/)(**int16_t**) | Converts the specified 16-bit signed integer to an equivalent single-precision floating-point number. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint32_t**) | Converts the specified 32-bit unsigned integer to an equivalent single-precision floating-point number. |
| static constexpr **float** [ToSingle](./tosingle/)(**int32_t**) | Converts the specified 32-bit signed integer to an equivalent single-precision floating-point number. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint64_t**) | Converts the specified 64-bit unsigned integer to an equivalent single-precision floating-point number. |
| static constexpr **float** [ToSingle](./tosingle/)(**int64_t**) | Converts the specified 64-bit signed integer to an equivalent single-precision floating-point number. |
| static constexpr **float** [ToSingle](./tosingle/)(**float**) | Returns the specified float number. |
| static constexpr **float** [ToSingle](./tosingle/)(**double**) | Converts the specified double-precision number to an equivalent single-precision floating-point number. |
| static **float** [ToSingle](./tosingle/)(const [Decimal](../decimal/)\&) | Converts the specified decimal number to an equivalent single-precision floating-point number. |
| static **float** [ToSingle](./tosingle/)(char_t) | Conversion is not supported. Always throws InvalidCastException. |
| static **float** [ToSingle](./tosingle/)([DateTime](../datetime/)) | Conversion is not supported. Always throws InvalidCastException. |
| static constexpr **float** [ToSingle](./tosingle/)(std::nullptr_t) | Converts the specified null-string to the equivalent single-precision floating-point value. |
| static **float** [ToSingle](./tosingle/)(const char_t *) | Converts the specified c-string containing the string representation of a number to the equivalent single-precision floating-point value. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&) | Converts the specified string containing the string representation of a number to the equivalent single-precision floating-point value. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent single-precision floating-point value using the provided formatting information. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent single-precision floating-point value using the provided formatting information and number style. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified boxed value to single-precision floating-point value. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**) | Converts the specified value to its string representation. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**) | Converts the specified value to its string representation. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**) | Converts the specified value to its string representation. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**) | Converts the specified value to its string representation. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**) | Converts the specified value to its string representation. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**) | Converts the specified value to its string representation. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**) | Converts the specified value to its string representation. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**) | Converts the specified value to its string representation. |
| static [String](../string/) [ToString](./tostring/)(**float**) | Converts the specified value to its string representation. |
| static [String](../string/) [ToString](./tostring/)(**double**) | Converts the specified value to its string representation. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&) | Converts the specified value to its string representation. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/)) | Converts the specified value to its string representation. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to string using the culture-specific format information. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to string using the culture-specific format information. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to string using the culture-specific format information. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to string using the culture-specific format information. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to string using the culture-specific format information. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to string using the culture-specific format information. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to string using the culture-specific format information. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to string using the culture-specific format information. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to string using the culture-specific format information. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to string using the culture-specific format information. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to string using the culture-specific format information. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to string using the culture-specific format information. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to its string representation using the specified string format and culture-specific format information provided by the specified [IFormatProvider](../iformatprovider/) object. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to its string representation using the specified string format and culture-specific format information provided by the specified [IFormatProvider](../iformatprovider/) object. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to its string representation using the specified string format and culture-specific format information provided by the specified [IFormatProvider](../iformatprovider/) object. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to its string representation using the specified string format and culture-specific format information provided by the specified [IFormatProvider](../iformatprovider/) object. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to its string representation using the specified string format and culture-specific format information provided by the specified [IFormatProvider](../iformatprovider/) object. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to its string representation using the specified string format and culture-specific format information provided by the specified [IFormatProvider](../iformatprovider/) object. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to its string representation using the specified string format and culture-specific format information provided by the specified [IFormatProvider](../iformatprovider/) object. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to its string representation using the specified string format and culture-specific format information provided by the specified [IFormatProvider](../iformatprovider/) object. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to its string representation using the specified string format and culture-specific format information provided by the specified [IFormatProvider](../iformatprovider/) object. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to its string representation using the specified string format and culture-specific format information provided by the specified [IFormatProvider](../iformatprovider/) object. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to its string representation using the specified string format and culture-specific format information provided by the specified [IFormatProvider](../iformatprovider/) object. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to its string representation using the specified string format and culture-specific format information provided by the specified [IFormatProvider](../iformatprovider/) object. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&) | Converts the specified value to string. |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&, const [String](../string/)\&) | Converts the specified value to string using the specified string format. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), std::nullptr_t) | Converts the specified array of unicode characters to string. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified array of unicode characters to string using the specified culture-specific format information provided by the specified [IFormatProvider](../iformatprovider/) object. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) | Returns the specified value; no conversion is performed. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Returns the specified value; no conversion is performed. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Returns the specified value; no conversion is performed. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Returns the specified value; no conversion is performed. |
| static [String](../string/) [ToString](./tostring/)(char_t, std::nullptr_t) | Returns the specified value; no conversion is performed. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Returns the specified value; no conversion is performed. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Returns the specified value; no conversion is performed. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Returns the specified value; no conversion is performed. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Returns the specified value; no conversion is performed. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, std::nullptr_t) | Returns the specified value; no conversion is performed. |
| static [String](../string/) [ToString](./tostring/)(**bool**, std::nullptr_t) | Converts the specified value to its string representation. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to its string representation. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Converts the specified value to its string representation. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Converts the specified value to its string representation. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified value to its string representation. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Converts the specified value to its string representation. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, std::nullptr_t) | Converts the specified value to its string representation. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, int) | Converts the specified integer value to its string representation in the specified base. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, int) | Converts the specified integer value to its string representation in the specified base. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, int) | Converts the specified integer value to its string representation in the specified base. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, int) | Converts the specified integer value to its string representation in the specified base. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified boxed value to its string representation. If the type of boxed value is [String](../string/), the specified string format is used during conversion. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**bool**) | Converts the specified boolean value to an equivalent 16-bit unsigned integer. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint8_t**) | Converts the specified 8-bit unsigned integer to an equivalent 16-bit unsigned integer. |
| static **uint16_t** [ToUInt16](./touint16/)(**int8_t**) | Converts the specified 8-bit signed integer to an equivalent 16-bit unsigned integer. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint16_t**) | Returns the specified 16-bit unsigned integer. |
| static **uint16_t** [ToUInt16](./touint16/)(**int16_t**) | Converts the specified 16-bit signed integer to an equivalent 16-bit unsigned integer. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint32_t**) | Converts the specified 32-bit unsigned integer to an equivalent 16-bit unsigned integer. |
| static **uint16_t** [ToUInt16](./touint16/)(**int32_t**) | Converts the specified 32-bit signed integer to an equivalent 16-bit unsigned integer. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint64_t**) | Converts the specified 64-bit unsigned integer to an equivalent 16-bit unsigned integer. |
| static **uint16_t** [ToUInt16](./touint16/)(**int64_t**) | Converts the specified 64-bit signed integer to an equivalent 16-bit unsigned integer. |
| static **uint16_t** [ToUInt16](./touint16/)(**float**) | Converts the specified float number to an equivalent 16-bit unsigned integer. |
| static **uint16_t** [ToUInt16](./touint16/)(**double**) | Converts the specified double number to an equivalent 16-bit unsigned integer. |
| static **uint16_t** [ToUInt16](./touint16/)(const [Decimal](../decimal/)\&) | Converts the specified decimal number to an equivalent 16-bit unsigned integer. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(char_t) | Converts the specified unicode character to an equivalent 16-bit unsigned integer. |
| static **uint16_t** [ToUInt16](./touint16/)([DateTime](../datetime/)) | Conversion is not supported. Always throws InvalidCastException. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(std::nullptr_t) | Converts the specified null-string to the equivalent unsigned 16-bit integer value. |
| static **uint16_t** [ToUInt16](./touint16/)(const char_t *) | Converts the specified c-string containing the string representation of a number to the equivalent unsigned 16-bit integer value. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&) | Converts the specified string containing the string representation of a number to the equivalent unsigned 16-bit integer value. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, int) | Converts the specified string containing the string representation of a number in the specified base to the equivalent unsigned 16-bit integer value. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent unsigned 16-bit integer value using the provided formatting information. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent unsigned 16-bit integer value using the provided formatting information and number style. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)([Enum](../enum/)) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified boxed value to equivalent unsigned 16-bit integer value. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**bool**) | Converts the specified boolean value to an equivalent 32-bit unsigned integer. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint8_t**) | Converts the specified 8-bit unsigned integer to an equivalent 32-bit unsigned integer. |
| static **uint32_t** [ToUInt32](./touint32/)(**int8_t**) | Converts the specified 8-bit signed integer to an equivalent 32-bit unsigned integer. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint16_t**) | Converts the specified 16-bit unsigned integer to an equivalent 32-bit unsigned integer. |
| static **uint32_t** [ToUInt32](./touint32/)(**int16_t**) | Converts the specified 16-bit signed integer to an equivalent 32-bit unsigned integer. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint32_t**) | Returns the specified 32-bit unsigned integer. |
| static **uint32_t** [ToUInt32](./touint32/)(**int32_t**) | Converts the specified 32-bit signed integer to an equivalent 32-bit unsigned integer. |
| static **uint32_t** [ToUInt32](./touint32/)(**uint64_t**) | Converts the specified 64-bit unsigned integer to an equivalent 32-bit unsigned integer. |
| static **uint32_t** [ToUInt32](./touint32/)(**int64_t**) | Converts the specified 64-bit signed integer to an equivalent 32-bit unsigned integer. |
| static **uint32_t** [ToUInt32](./touint32/)(**float**) | Converts the specified float number to an equivalent 32-bit unsigned integer. |
| static **uint32_t** [ToUInt32](./touint32/)(**double**) | Converts the specified double number to an equivalent 32-bit unsigned integer. |
| static **uint32_t** [ToUInt32](./touint32/)(const [Decimal](../decimal/)\&) | Converts the specified decimal number to an equivalent 32-bit unsigned integer. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(char_t) | Converts the specified unicode character to an equivalent 32-bit unsigned integer. |
| static **uint32_t** [ToUInt32](./touint32/)([DateTime](../datetime/)) | Conversion is not supported. Always throws InvalidCastException. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(std::nullptr_t) | Converts the specified null-string to the equivalent unsigned 32-bit integer value. |
| static **uint32_t** [ToUInt32](./touint32/)(const char_t *) | Converts the specified c-string containing the string representation of a number to the equivalent unsigned 32-bit integer value. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&) | Converts the specified string containing the string representation of a number to the equivalent unsigned 32-bit integer value. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, int) | Converts the specified string containing the string representation of a number in the specified base to the equivalent unsigned 32-bit integer value. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent unsigned 32-bit integer value using the provided formatting information. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent unsigned 32-bit integer value using the provided formatting information and number style. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)([Enum](../enum/)) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified boxed value to equivalent unsigned 32-bit integer value. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**bool**) | Converts the specified boolean value to an equivalent 64-bit unsigned integer. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint8_t**) | Converts the specified 8-bit unsigned integer to an equivalent 64-bit unsigned integer. |
| static **uint64_t** [ToUInt64](./touint64/)(**int8_t**) | Converts the specified 8-bit signed integer to an equivalent 64-bit unsigned integer. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint16_t**) | Converts the specified 16-bit unsigned integer to an equivalent 64-bit unsigned integer. |
| static **uint64_t** [ToUInt64](./touint64/)(**int16_t**) | Converts the specified 16-bit signed integer to an equivalent 64-bit unsigned integer. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint32_t**) | Converts the specified 32-bit unsigned integer to an equivalent 64-bit unsigned integer. |
| static **uint64_t** [ToUInt64](./touint64/)(**int32_t**) | Converts the specified 32-bit signed integer to an equivalent 64-bit unsigned integer. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint64_t**) | Returns the specified 64-bit unsigned integer. |
| static **uint64_t** [ToUInt64](./touint64/)(**int64_t**) | Converts the specified 64-bit signed integer to an equivalent 64-bit unsigned integer. |
| static **uint64_t** [ToUInt64](./touint64/)(**float**) | Converts the specified float number to an equivalent 64-bit unsigned integer. |
| static **uint64_t** [ToUInt64](./touint64/)(**double**) | Converts the specified double number to an equivalent 64-bit unsigned integer. |
| static **uint64_t** [ToUInt64](./touint64/)(const [Decimal](../decimal/)\&) | Converts the specified decimal number to an equivalent 64-bit unsigned integer. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(char_t) | Converts the specified unicode character to an equivalent 64-bit unsigned integer. |
| static **uint64_t** [ToUInt64](./touint64/)([DateTime](../datetime/)) | Conversion is not supported. Always throws InvalidCastException. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(std::nullptr_t) | Converts the specified null-string to the equivalent unsigned 64-bit integer value. |
| static **uint64_t** [ToUInt64](./touint64/)(const char_t *) | Converts the specified c-string containing the string representation of a number to the equivalent unsigned 64-bit integer value. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&) | Converts the specified string containing the string representation of a number to the equivalent unsigned 64-bit integer value. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, int) | Converts the specified string containing the string representation of a number in the specified base to the equivalent unsigned 64-bit integer value. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent unsigned 64-bit integer value using the provided formatting information. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified string containing the string representation of a number to the equivalent unsigned 64-bit integer value using the provided formatting information and number style. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)([Enum](../enum/)) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converts the specified boxed value to equivalent unsigned 64-bit integer value. |
## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)