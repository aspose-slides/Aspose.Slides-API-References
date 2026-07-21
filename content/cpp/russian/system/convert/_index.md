---
title: Convert
second_title: Справочник API Aspose.Slides для C++
description: "Структура, содержащая методы, выполняющие преобразование значений одного типа в значения другого типа. Этот тип должен быть размещён в стеке и передаваться функциям по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа."
type: docs
weight: 1535
url: /ru/system/convert/
---
## Конвертировать структуру

Структура, содержащая методы, выполняющие преобразование значений одного типа в значения другого типа. Этот тип должен быть размещён в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](../smartptr/) для управления объектами этого типа.

```cpp
class Convert
```

## Методы

| Method | Описание |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&) | НЕ РЕАЛИЗОВАНО. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64CharArray](./frombase64chararray/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Декодирует данные, закодированные в base-64, представленные как диапазон в массиве символов Unicode. |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64String](./frombase64string/)(const [String](../string/)\&) | Декодирует данные, закодированные в base-64, представленные в виде строки. |
| static [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Возвращает значение TypeCode, представляющее тип указанного упакованного значения. |
| static std::enable_if_t<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\> [IsDBNull](./isdbnull/)(const T\&) | НЕ РЕАЛИЗОВАНО. |
| static **bool** [IsDBNull](./isdbnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | НЕ РЕАЛИЗОВАНО. Фейковая реализация, проверяет, является ли значение nullptr. |
| static Target [To](./to/)(const Source\&) |  |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, **bool**) | Кодирует в base-64 диапазон элементов указанного массива байтов и сохраняет закодированные данные как массив символов Unicode. |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, [Base64FormattingOptions](../base64formattingoptions/)) | Кодирует в base-64 диапазон элементов указанного массива байтов и сохраняет закодированные данные как массив символов Unicode. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**) | Кодирует в base-64 элементы указанного массива байтов и возвращает закодированные данные в виде строки. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, **bool**) | Кодирует в base-64 диапазон элементов указанного массива байтов и возвращает закодированные данные в виде строки. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, [Base64FormattingOptions](../base64formattingoptions/)) | Кодирует в base-64 элементы указанного массива байтов и возвращает закодированные данные в виде строки. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, [Base64FormattingOptions](../base64formattingoptions/)) | Кодирует в base-64 диапазон элементов указанного массива байтов и возвращает закодированные данные в виде строки. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**bool**) | Возвращает указанное логическое значение. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint8_t**) | Преобразует указанное 8-битное беззнаковое целое в эквивалентное логическое значение. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int8_t**) | Преобразует указанное 8-битное знаковое целое в эквивалентное логическое значение. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint16_t**) | Преобразует указанное 16-битное беззнаковое целое в эквивалентное логическое значение. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int16_t**) | Преобразует указанное 16-битное знаковое целое в эквивалентное логическое значение. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint32_t**) | Преобразует указанное 32-битное беззнаковое целое в эквивалентное логическое значение. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int32_t**) | Преобразует указанное 32-битное знаковое целое в эквивалентное логическое значение. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint64_t**) | Преобразует указанное 64-битное беззнаковое целое в эквивалентное логическое значение. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int64_t**) | Преобразует указанное 64-битное знаковое целое в эквивалентное логическое значение. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**float**) | Преобразует указанное число с плавающей точкой типа float в эквивалентное логическое значение. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**double**) | Преобразует указанное число с плавающей точкой типа double в эквивалентное логическое значение. |
| static **bool** [ToBoolean](./toboolean/)(const [Decimal](../decimal/)\&) | Преобразует указанное десятичное число в эквивалентное логическое значение. |
| static **bool** [ToBoolean](./toboolean/)(char_t) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static **bool** [ToBoolean](./toboolean/)([DateTime](../datetime/)) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static constexpr **bool** [ToBoolean](./toboolean/)(std::nullptr_t) | Преобразует указанную нулевую строку в эквивалентное логическое значение. |
| static **bool** [ToBoolean](./toboolean/)(const char_t *) | Преобразует указанную C-строку в значение типа bool. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&) | Преобразует указанную строку в значение типа bool. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку в значение типа bool. |
| static **bool** [ToBoolean](./toboolean/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное упакованное значение в эквивалентное логическое значение. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**bool**) | Преобразует указанное логическое значение в эквивалентное 8-битное беззнаковое целое. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**uint8_t**) | Возвращает указанное 8-битное беззнаковое целое. |
| static **uint8_t** [ToByte](./tobyte/)(**int8_t**) | Преобразует указанное 8-битное знаковое целое в эквивалентное 8-битное беззнаковое целое. |
| static **uint8_t** [ToByte](./tobyte/)(**uint16_t**) | Преобразует указанное 16-битное беззнаковое целое в эквивалентное 8-битное беззнаковое целое. |
| static **uint8_t** [ToByte](./tobyte/)(**int16_t**) | Преобразует указанное 16-битное знаковое целое в эквивалентное 8-битное беззнаковое целое. |
| static **uint8_t** [ToByte](./tobyte/)(**uint32_t**) | Преобразует указанное 32-битное беззнаковое целое в эквивалентное 8-битное беззнаковое целое. |
| static **uint8_t** [ToByte](./tobyte/)(**int32_t**) | Преобразует указанное 32-битное знаковое целое в эквивалентное 8-битное беззнаковое целое. |
| static **uint8_t** [ToByte](./tobyte/)(**uint64_t**) | Преобразует указанное 64-битное беззнаковое целое в эквивалентное 8-битное беззнаковое целое. |
| static **uint8_t** [ToByte](./tobyte/)(**int64_t**) | Преобразует указанное 64-битное знаковое целое в эквивалентное 8-битное беззнаковое целое. |
| static **uint8_t** [ToByte](./tobyte/)(**float**) | Преобразует указанное число типа float в эквивалентное 8-битное беззнаковое целое. |
| static **uint8_t** [ToByte](./tobyte/)(**double**) | Преобразует указанное число типа double в эквивалентное 8-битное беззнаковое целое. |
| static **uint8_t** [ToByte](./tobyte/)(const [Decimal](../decimal/)\&) | Преобразует указанное десятичное число в эквивалентное 8-битное беззнаковое целое. |
| static **uint8_t** [ToByte](./tobyte/)(char_t) | Преобразует указанный символ Unicode в эквивалентное 8-битное беззнаковое целое. |
| static **uint8_t** [ToByte](./tobyte/)([DateTime](../datetime/)) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(std::nullptr_t) | Преобразует указанную нулевую строку в эквивалентное беззнаковое 8-битное целое. |
| static **uint8_t** [ToByte](./tobyte/)(const char_t *) | Преобразует указанную C-строку, содержащую строковое представление числа, в эквивалентное беззнаковое 8-битное целое. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 8-битное целое. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, int) | Преобразует указанную строку, содержащую строковое представление числа в указанной системе счисления, в эквивалентное беззнаковое 8-битное целое. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 8-битное целое с использованием предоставленной информации о форматировании. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 8-битное целое с использованием предоставленной информации о форматировании и стиле числа. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)([Enum](../enum/)) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное упакованное значение в эквивалентное беззнаковое 8-битное целое. |
| static char_t [ToChar](./tochar/)(**bool**) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(**uint8_t**) | Преобразует указанное 8-битное беззнаковое целое в эквивалентный символ Unicode. |
| static char_t [ToChar](./tochar/)(**int8_t**) | Преобразует указанное 8-битное знаковое целое в эквивалентный символ Unicode. |
| static constexpr char_t [ToChar](./tochar/)(**uint16_t**) | Преобразует указанное 16-битное беззнаковое целое в эквивалентный символ Unicode. |
| static char_t [ToChar](./tochar/)(**int16_t**) | Преобразует указанное 16-битное знаковое целое в эквивалентный символ Unicode. |
| static char_t [ToChar](./tochar/)(**uint32_t**) | Преобразует указанное 32-битное беззнаковое целое в эквивалентный символ Unicode. |
| static char_t [ToChar](./tochar/)(**int32_t**) | Преобразует указанное 32-битное знаковое целое в эквивалентный символ Unicode. |
| static char_t [ToChar](./tochar/)(**uint64_t**) | Преобразует указанное 64-битное беззнаковое целое в эквивалентный символ Unicode. |
| static char_t [ToChar](./tochar/)(**int64_t**) | Преобразует указанное 64-битное знаковое целое в эквивалентный символ Unicode. |
| static char_t [ToChar](./tochar/)(**float**) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static char_t [ToChar](./tochar/)(**double**) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static char_t [ToChar](./tochar/)(const [Decimal](../decimal/)\&) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(char_t) | Возвращает указанный символ Unicode. |
| static char_t [ToChar](./tochar/)([DateTime](../datetime/)) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static char_t [ToChar](./tochar/)(const char_t *) | Преобразует первый и единственный символ указанной C-строки в значение типа char_t. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&) | Преобразует первый и единственный символ указанной строки в значение типа char_t. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует первый и единственный символ указанной строки в значение типа char_t. |
| static char_t [ToChar](./tochar/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное упакованное значение в эквивалентный символ Unicode. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**bool**) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint8_t**) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int8_t**) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint16_t**) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int16_t**) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint32_t**) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int32_t**) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint64_t**) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int64_t**) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**float**) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**double**) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [Decimal](../decimal/)\&) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(char_t) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static constexpr [DateTime](../datetime/) [ToDateTime](./todatetime/)([DateTime](../datetime/)) | Возвращает указанную дату и время. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&) | Преобразует указанную строку в экземпляр класса [DateTime](../datetime/). |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку в экземпляр класса [DateTime](../datetime/) с использованием предоставленной информации о форматировании. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное упакованное значение в эквивалентное значение [DateTime](../datetime/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**bool**) | Преобразует указанное логическое значение в эквивалентное десятичное число. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint8_t**) | Преобразует указанное 8-битное беззнаковое целое в эквивалентное десятичное число. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int8_t**) | Преобразует указанное 8-битное знаковое целое в эквивалентное десятичное число. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint16_t**) | Преобразует указанное 16-битное беззнаковое целое в эквивалентное десятичное число. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int16_t**) | Преобразует указанное 16-битное знаковое целое в эквивалентное десятичное число. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint32_t**) | Преобразует указанное 32-битное беззнаковое целое в эквивалентное десятичное число. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int32_t**) | Преобразует указанное 32-битное знаковое целое в эквивалентное десятичное число. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint64_t**) | Преобразует указанное 64-битное беззнаковое целое в эквивалентное десятичное число. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int64_t**) | Преобразует указанное 64-битное знаковое целое в эквивалентное десятичное число. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**float**) | Преобразует указанное число типа float в эквивалентное десятичное число. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**double**) | Преобразует указанное число типа double в эквивалентное десятичное число. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [Decimal](../decimal/)\&) | Возвращает указанное десятичное число. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(char_t) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)([DateTime](../datetime/)) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(std::nullptr_t) | Преобразует указанную нулевую строку в эквивалентное значение [Decimal](../decimal/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const char_t *) | Преобразует указанную C-строку, содержащую строковое представление числа, в эквивалентное значение [Decimal](../decimal/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение [Decimal](../decimal/). |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение [Decimal](../decimal/) с использованием предоставленной информации о форматировании. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение [Decimal](../decimal/) с использованием указанных стилей числа и информации о форматировании. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное упакованное значение в эквивалентное значение [Decimal](../decimal/). |
| static constexpr **double** [ToDouble](./todouble/)(**bool**) | Преобразует указанное логическое значение в эквивалентное число двойной точности. |
| static constexpr **double** [ToDouble](./todouble/)(**uint8_t**) | Преобразует указанное 8-битное беззнаковое целое в эквивалентное число двойной точности. |
| static constexpr **double** [ToDouble](./todouble/)(**int8_t**) | Преобразует указанное 8-битное знаковое целое в эквивалентное число двойной точности. |
| static constexpr **double** [ToDouble](./todouble/)(**uint16_t**) | Преобразует указанное 16-битное беззнаковое целое в эквивалентное число двойной точности. |
| static constexpr **double** [ToDouble](./todouble/)(**int16_t**) | Преобразует указанное 16-битное знаковое целое в эквивалентное число двойной точности. |
| static constexpr **double** [ToDouble](./todouble/)(**uint32_t**) | Преобразует указанное 32-битное беззнаковое целое в эквивалентное число двойной точности. |
| static constexpr **double** [ToDouble](./todouble/)(**int32_t**) | Преобразует указанное 32-битное знаковое целое в эквивалентное число двойной точности. |
| static constexpr **double** [ToDouble](./todouble/)(**uint64_t**) | Преобразует указанное 64-битное беззнаковое целое в эквивалентное число двойной точности. |
| static constexpr **double** [ToDouble](./todouble/)(**int64_t**) | Преобразует указанное 64-битное знаковое целое в эквивалентное число двойной точности. |
| static constexpr **double** [ToDouble](./todouble/)(**float**) | Преобразует указанное число типа float в эквивалентное число двойной точности. |
| static constexpr **double** [ToDouble](./todouble/)(**double**) | Возвращает указанное число двойной точности. |
| static **double** [ToDouble](./todouble/)(const [Decimal](../decimal/)\&) | Преобразует указанное десятичное число в эквивалентное число двойной точности. |
| static **double** [ToDouble](./todouble/)(char_t) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static **double** [ToDouble](./todouble/)([DateTime](../datetime/)) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static constexpr **double** [ToDouble](./todouble/)(std::nullptr_t) | Преобразует указанную нулевую строку в эквивалентное число двойной точности. |
| static **double** [ToDouble](./todouble/)(const char_t *) | Преобразует указанную C-строку, содержащую строковое представление числа, в эквивалентное число двойной точности. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное число двойной точности. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное число двойной точности с использованием предоставленной информации о форматировании. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное число двойной точности с использованием предоставленной информации о форматировании и стиле числа. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное упакованное значение в число двойной точности. Если тип упакованного значения — [String](../string/), используется указанный строковый формат при конверсии. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**bool**) | Преобразует указанное логическое значение в эквивалентное 16-битное знаковое целое. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**uint8_t**) | Преобразует указанное 8-битное беззнаковое целое в эквивалентное 16-битное знаковое целое. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int8_t**) | Преобразует указанное 8-битное знаковое целое в эквивалентное 16-битное знаковое целое. |
| static **int16_t** [ToInt16](./toint16/)(**uint16_t**) | Преобразует указанное 16-битное беззнаковое целое в эквивалентное 16-битное знаковое целое. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int16_t**) | Возвращает указанное 16-битное знаковое целое. |
| static **int16_t** [ToInt16](./toint16/)(**uint32_t**) | Преобразует указанное 32-битное беззнаковое целое в эквивалентное 16-битное знаковое целое. |
| static **int16_t** [ToInt16](./toint16/)(**int32_t**) | Преобразует указанное 32-битное знаковое целое в эквивалентное 16-битное знаковое целое. |
| static **int16_t** [ToInt16](./toint16/)(**uint64_t**) | Преобразует указанное 64-битное беззнаковое целое в эквивалентное 16-битное знаковое целое. |
| static **int16_t** [ToInt16](./toint16/)(**int64_t**) | Преобразует указанное 64-битное знаковое целое в эквивалентное 16-битное знаковое целое. |
| static **int16_t** [ToInt16](./toint16/)(**float**) | Преобразует указанное число типа float в эквивалентное 16-битное знаковое целое. |
| static **int16_t** [ToInt16](./toint16/)(**double**) | Преобразует указанное число типа double в эквивалентное 16-битное знаковое целое. |
| static **int16_t** [ToInt16](./toint16/)(const [Decimal](../decimal/)\&) | Преобразует указанное десятичное число в эквивалентное 16-битное знаковое целое. |
| static **int16_t** [ToInt16](./toint16/)(char_t) | Преобразует указанный символ Unicode в эквивалентное 16-битное знаковое целое. |
| static **int16_t** [ToInt16](./toint16/)([DateTime](../datetime/)) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static constexpr **int16_t** [ToInt16](./toint16/)(std::nullptr_t) | Преобразует указанную нулевую строку в эквивалентное 16-битное целое. |
| static **int16_t** [ToInt16](./toint16/)(const char_t *) | Преобразует указанную C-строку, содержащую строковое представление числа, в эквивалентное 16-битное целое. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 16-битное целое. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, int) | Преобразует указанную строку, содержащую строковое представление числа в указанной системе счисления, в эквивалентное 16-битное целое. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 16-битное целое с использованием предоставленной информации о форматировании. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 16-битное целое с использованием предоставленной информации о форматировании и стиле числа. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)([Enum](../enum/)) |  |
| static **int16_t** [ToInt16](./toint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное упакованное значение в эквивалентное 16-битное целое. |
| static constexpr int [ToInt32](./toint32/)(**bool**) | Преобразует указанное логическое значение в эквивалентное 32-битное знаковое целое. |
| static constexpr int [ToInt32](./toint32/)(**uint8_t**) | Преобразует указанное 8-битное беззнаковое целое в эквивалентное 32-битное знаковое целое. |
| static constexpr int [ToInt32](./toint32/)(**int8_t**) | Преобразует указанное 8-битное знаковое целое в эквивалентное 32-битное знаковое целое. |
| static constexpr int [ToInt32](./toint32/)(**uint16_t**) | Преобразует указанное 16-битное беззнаковое целое в эквивалентное 32-битное знаковое целое. |
| static constexpr int [ToInt32](./toint32/)(**int16_t**) | Преобразует указанное 16-битное знаковое целое в эквивалентное 32-битное знаковое целое. |
| static int [ToInt32](./toint32/)(**uint32_t**) | Преобразует указанное 32-битное беззнаковое целое в эквивалентное 32-битное знаковое целое. |
| static constexpr int [ToInt32](./toint32/)(**int32_t**) | Возвращает указанное 32-битное знаковое целое. |
| static int [ToInt32](./toint32/)(**uint64_t**) | Преобразует указанное 64-битное беззнаковое целое в эквивалентное 32-битное знаковое целое. |
| static int [ToInt32](./toint32/)(**int64_t**) | Преобразует указанное 64-битное знаковое целое в эквивалентное 32-битное знаковое целое. |
| static int [ToInt32](./toint32/)(**float**) | Преобразует указанное число типа float в эквивалентное 32-битное знаковое целое. |
| static int [ToInt32](./toint32/)(**double**) | Преобразует указанное число типа double в эквивалентное 32-битное знаковое целое. |
| static int [ToInt32](./toint32/)(const [Decimal](../decimal/)\&) | Преобразует указанное десятичное число в эквивалентное 32-битное знаковое целое. |
| static constexpr int [ToInt32](./toint32/)(char_t) | Преобразует указанный символ Unicode в эквивалентное 32-битное знаковое целое. |
| static int [ToInt32](./toint32/)([DateTime](../datetime/)) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static constexpr int [ToInt32](./toint32/)(std::nullptr_t) | Преобразует указанную нулевую строку в эквивалентное 32-битное целое. |
| static int [ToInt32](./toint32/)(const char_t *) | Преобразует указанную C-строку, содержащую строковое представление числа, в эквивалентное 32-битное целое. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 32-битное целое. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, int) | Преобразует указанную строку, содержащую строковое представление числа в указанной системе счисления, в эквивалентное 32-битное целое. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 32-битное целое с использованием предоставленной информации о форматировании. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 32-битное целое с использованием предоставленной информации о форматировании и стиле числа. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [ToInt32](./toint32/)([Enum](../enum/)) |  |
| static int [ToInt32](./toint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное упакованное значение в эквивалентное 32-битное целое. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**bool**) | Преобразует указанное логическое значение в эквивалентное 64-битное знаковое целое. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint8_t**) | Преобразует указанное 8-битное беззнаковое целое в эквивалентное 64-битное знаковое целое. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int8_t**) | Преобразует указанное 8-битное знаковое целое в эквивалентное 64-битное знаковое целое. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint16_t**) | Преобразует указанное 16-битное беззнаковое целое в эквивалентное 64-битное знаковое целое. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int16_t**) | Преобразует указанное 16-битное знаковое целое в эквивалентное 64-битное знаковое целое. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint32_t**) | Преобразует указанное 32-битное беззнаковое целое в эквивалентное 64-битное знаковое целое. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int32_t**) | Преобразует указанное 32-битное знаковое целое в эквивалентное 64-битное знаковое целое. |
| static **int64_t** [ToInt64](./toint64/)(**uint64_t**) | Преобразует указанное 64-битное беззнаковое целое в эквивалентное 64-битное знаковое целое. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int64_t**) | Возвращает указанное 64-битное знаковое целое. |
| static **int64_t** [ToInt64](./toint64/)(**float**) | Преобразует указанное число типа float в эквивалентное 64-битное знаковое целое. |
| static **int64_t** [ToInt64](./toint64/)(**double**) | Преобразует указанное число типа double в эквивалентное 64-битное знаковое целое. |
| static **int64_t** [ToInt64](./toint64/)(const [Decimal](../decimal/)\&) | Преобразует указанное десятичное число в эквивалентное 64-битное знаковое целое. |
| static constexpr **int64_t** [ToInt64](./toint64/)(char_t) | Преобразует указанный символ Unicode в эквивалентное 64-битное знаковое целое. |
| static **int64_t** [ToInt64](./toint64/)([DateTime](../datetime/)) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static constexpr **int64_t** [ToInt64](./toint64/)(std::nullptr_t) | Преобразует указанную нулевую строку в эквивалентное 64-битное целое. |
| static **int64_t** [ToInt64](./toint64/)(const char_t *) | Преобразует указанную C-строку, содержащую строковое представление числа, в эквивалентное 64-битное целое. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 64-битное целое. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, int) | Преобразует указанную строку, содержащую строковое представление числа в указанной системе счисления, в эквивалентное 64-битное целое. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 64-битное целое с использованием предоставленной информации о форматировании. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 64-битное целое с использованием предоставленной информации о форматировании и стиле числа. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)([Enum](../enum/)) |  |
| static **int64_t** [ToInt64](./toint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное упакованное значение в эквивалентное 64-битное целое. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**bool**) | Преобразует указанное логическое значение в эквивалентное 8-битное знаковое целое. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint8_t**) | Преобразует указанное 8-битное беззнаковое целое в эквивалентное 8-битное знаковое целое. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**int8_t**) | Возвращает указанное 8-битное знаковое целое. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint16_t**) | Преобразует указанное 16-битное беззнаковое целое в эквивалентное 8-битное знаковое целое. |
| static **int8_t** [ToSByte](./tosbyte/)(**int16_t**) | Преобразует указанное 16-битное знаковое целое в эквивалентное 8-битное знаковое целое. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint32_t**) | Преобразует указанное 32-битное беззнаковое целое в эквивалентное 8-битное знаковое целое. |
| static **int8_t** [ToSByte](./tosbyte/)(**int32_t**) | Преобразует указанное 32-битное знаковое целое в эквивалентное 8-битное знаковое целое. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint64_t**) | Преобразует указанное 64-битное беззнаковое целое в эквивалентное 8-битное знаковое целое. |
| static **int8_t** [ToSByte](./tosbyte/)(**int64_t**) | Преобразует указанное 64-битное знаковое целое в эквивалентное 8-битное знаковое целое. |
| static **int8_t** [ToSByte](./tosbyte/)(**float**) | Преобразует указанное число типа float в эквивалентное 8-битное знаковое целое. |
| static **int8_t** [ToSByte](./tosbyte/)(**double**) | Преобразует указанное число типа double в эквивалентное 8-битное знаковое целое. |
| static **int8_t** [ToSByte](./tosbyte/)(const [Decimal](../decimal/)\&) | Преобразует указанное десятичное число в эквивалентное 8-битное знаковое целое. |
| static **int8_t** [ToSByte](./tosbyte/)(char_t) | Преобразует указанный символ Unicode в эквивалентное 8-битное знаковое целое. |
| static **int8_t** [ToSByte](./tosbyte/)([DateTime](../datetime/)) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(std::nullptr_t) | Преобразует указанную нулевую строку в эквивалентное 8-битное целое. |
| static **int8_t** [ToSByte](./tosbyte/)(const char_t *) | Преобразует указанную C-строку, содержащую строковое представление числа, в эквивалентное 8-битное целое. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 8-битное целое. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, int) | Преобразует указанную строку, содержащую строковое представление числа в указанной системе счисления, в эквивалентное 8-битное целое. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 8-битное целое с использованием предоставленной информации о форматировании. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное 8-битное целое с использованием предоставленной информации о форматировании и стиле числа. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)([Enum](../enum/)) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное упакованное значение в эквивалентное 8-битное целое. |
| static constexpr **float** [ToSingle](./tosingle/)(**bool**) | Преобразует указанное логическое значение в эквивалентное число одинарной точности. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint8_t**) | Преобразует указанное 8-битное беззнаковое целое в эквивалентное число одинарной точности. |
| static constexpr **float** [ToSingle](./tosingle/)(**int8_t**) | Преобразует указанное 8-битное знаковое целое в эквивалентное число одинарной точности. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint16_t**) | Преобразует указанное 16-битное беззнаковое целое в эквивалентное число одинарной точности. |
| static constexpr **float** [ToSingle](./tosingle/)(**int16_t**) | Преобразует указанное 16-битное знаковое целое в эквивалентное число одинарной точности. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint32_t**) | Преобразует указанное 32-битное беззнаковое целое в эквивалентное число одинарной точности. |
| static constexpr **float** [ToSingle](./tosingle/)(**int32_t**) | Преобразует указанное 32-битное знаковое целое в эквивалентное число одинарной точности. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint64_t**) | Преобразует указанное 64-битное беззнаковое целое в эквивалентное число одинарной точности. |
| static constexpr **float** [ToSingle](./tosingle/)(**int64_t**) | Преобразует указанное 64-битное знаковое целое в эквивалентное число одинарной точности. |
| static constexpr **float** [ToSingle](./tosingle/)(**float**) | Возвращает указанное число типа float. |
| static constexpr **float** [ToSingle](./tosingle/)(**double**) | Преобразует указанное число двойной точности в эквивалентное число одинарной точности. |
| static **float** [ToSingle](./tosingle/)(const [Decimal](../decimal/)\&) | Преобразует указанное десятичное число в эквивалентное число одинарной точности. |
| static **float** [ToSingle](./tosingle/)(char_t) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static **float** [ToSingle](./tosingle/)([DateTime](../datetime/)) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static constexpr **float** [ToSingle](./tosingle/)(std::nullptr_t) | Преобразует указанную нулевую строку в эквивалентное число одинарной точности. |
| static **float** [ToSingle](./tosingle/)(const char_t *) | Преобразует указанную C-строку, содержащую строковое представление числа, в эквивалентное число одинарной точности. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное число одинарной точности. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное число одинарной точности с использованием предоставленной информации о форматировании. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное число одинарной точности с использованием предоставленной информации о форматировании и стиле числа. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное упакованное значение в число одинарной точности. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**) | Преобразует указанное значение в его строковое представление. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**) | Преобразует указанное значение в его строковое представление. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**) | Преобразует указанное значение в его строковое представление. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**) | Преобразует указанное значение в его строковое представление. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**) | Преобразует указанное значение в его строковое представление. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**) | Преобразует указанное значение в его строковое представление. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**) | Преобразует указанное значение в его строковое представление. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**) | Преобразует указанное значение в его строковое представление. |
| static [String](../string/) [ToString](./tostring/)(**float**) | Преобразует указанное значение в его строковое представление. |
| static [String](../string/) [ToString](./tostring/)(**double**) | Преобразует указанное значение в его строковое представление. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&) | Преобразует указанное значение в его строковое представление. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/)) | Преобразует указанное значение в его строковое представление. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в строку, используя культурно-специфическую информацию о формате. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в строку, используя культурно-специфическую информацию о формате. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в строку, используя культурно-специфическую информацию о формате. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в строку, используя культурно-специфическую информацию о формате. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в строку, используя культурно-специфическую информацию о формате. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в строку, используя культурно-специфическую информацию о формате. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в строку, используя культурно-специфическую информацию о формате. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в строку, используя культурно-специфическую информацию о формате. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в строку, используя культурно-специфическую информацию о формате. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в строку, используя культурно-специфическую информацию о формате. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в строку, используя культурно-специфическую информацию о формате. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в строку, используя культурно-специфическую информацию о формате. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в его строковое представление, используя указанный строковый формат и культурно-специфическую информацию о формате, предоставленные объектом [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в его строковое представление, используя указанный строковый формат и культурно-специфическую информацию о формате, предоставленные объектом [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в его строковое представление, используя указанный строковый формат и культурно-специфическую информацию о формате, предоставленные объектом [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в его строковое представление, используя указанный строковый формат и культурно-специфическую информацию о формате, предоставленные объектом [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в его строковое представление, используя указанный строковый формат и культурно-специфическую информацию о формате, предоставленные объектом [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в его строковое представление, используя указанный строковый формат и культурно-специфическую информацию о формате, предоставленные объектом [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в его строковое представление, используя указанный строковый формат и культурно-специфическую информацию о формате, предоставленные объектом [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в его строковое представление, используя указанный строковый формат и культурно-специфическую информацию о формате, предоставленные объектом [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в его строковое представление, используя указанный строковый формат и культурно-специфическую информацию о формате, предоставленные объектом [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в его строковое представление, используя указанный строковый формат и культурно-специфическую информацию о формате, предоставленные объектом [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в его строковое представление, используя указанный строковый формат и культурно-специфическую информацию о формате, предоставленные объектом [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в его строковое представление, используя указанный строковый формат и культурно-специфическую информацию о формате, предоставленные объектом [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&) | Преобразует указанное значение в строку. |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&, const [String](../string/)\&) | Преобразует указанное значение в строку, используя указанный строковый формат. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), std::nullptr_t) | Преобразует указанный массив символов Unicode в строку. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанный массив символов Unicode в строку, используя предоставленную культурно-специфическую информацию о формате, предоставленную объектом [IFormatProvider](../iformatprovider/). |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) | Возвращает указанное значение; преобразование не выполняется. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Возвращает указанное значение; преобразование не выполняется. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Возвращает указанное значение; преобразование не выполняется. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Возвращает указанное значение; преобразование не выполняется. |
| static [String](../string/) [ToString](./tostring/)(char_t, std::nullptr_t) | Возвращает указанное значение; преобразование не выполняется. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Возвращает указанное значение; преобразование не выполняется. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Возвращает указанное значение; преобразование не выполняется. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Возвращает указанное значение; преобразование не выполняется. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Возвращает указанное значение; преобразование не выполняется. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, std::nullptr_t) | Возвращает указанное значение; преобразование не выполняется. |
| static [String](../string/) [ToString](./tostring/)(**bool**, std::nullptr_t) | Преобразует указанное значение в его строковое представление. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в его строковое представление. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Преобразует указанное значение в его строковое представление. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Преобразует указанное значение в его строковое представление. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное значение в его строковое представление. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Преобразует указанное значение в его строковое представление. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, std::nullptr_t) | Преобразует указанное значение в его строковое представление. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, int) | Преобразует указанное целочисленное значение в его строковое представление в указанной системе счисления. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, int) | Преобразует указанное целочисленное значение в его строковое представление в указанной системе счисления. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, int) | Преобразует указанное целочисленное значение в его строковое представление в указанной системе счисления. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, int) | Преобразует указанное целочисленное значение в его строковое представление в указанной системе счисления. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное упакованное значение в его строковое представление. Если тип упакованного значения — [String](../string/), используется указанный строковый формат при конверсии. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**bool**) | Преобразует указанное логическое значение в эквивалентное 16-битное беззнаковое целое. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint8_t**) | Преобразует указанное 8-битное беззнаковое целое в эквивалентное 16-битное беззнаковое целое. |
| static **uint16_t** [ToUInt16](./touint16/)(**int8_t**) | Преобразует указанное 8-битное знаковое целое в эквивалентное 16-битное беззнаковое целое. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint16_t**) | Возвращает указанное 16-битное беззнаковое целое. |
| static **uint16_t** [ToUInt16](./touint16/)(**int16_t**) | Преобразует указанное 16-битное знаковое целое в эквивалентное 16-битное беззнаковое целое. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint32_t**) | Преобразует указанное 32-битное беззнаковое целое в эквивалентное 16-битное беззнаковое целое. |
| static **uint16_t** [ToUInt16](./touint16/)(**int32_t**) | Преобразует указанное 32-битное знаковое целое в эквивалентное 16-битное беззнаковое целое. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint64_t**) | Преобразует указанное 64-битное беззнаковое целое в эквивалентное 16-битное беззнаковое целое. |
| static **uint16_t** [ToUInt16](./touint16/)(**int64_t**) | Преобразует указанное 64-битное знаковое целое в эквивалентное 16-битное беззнаковое целое. |
| static **uint16_t** [ToUInt16](./touint16/)(**float**) | Преобразует указанное число типа float в эквивалентное 16-битное беззнаковое целое. |
| static **uint16_t** [ToUInt16](./touint16/)(**double**) | Преобразует указанное число типа double в эквивалентное 16-битное беззнаковое целое. |
| static **uint16_t** [ToUInt16](./touint16/)(const [Decimal](../decimal/)\&) | Преобразует указанное десятичное число в эквивалентное 16-битное беззнаковое целое. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(char_t) | Преобразует указанный символ Unicode в эквивалентное 16-битное беззнаковое целое. |
| static **uint16_t** [ToUInt16](./touint16/)([DateTime](../datetime/)) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(std::nullptr_t) | Преобразует указанную нулевую строку в эквивалентное беззнаковое 16-битное целое. |
| static **uint16_t** [ToUInt16](./touint16/)(const char_t *) | Преобразует указанную C-строку, содержащую строковое представление числа, в эквивалентное беззнаковое 16-битное целое. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 16-битное целое. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, int) | Преобразует указанную строку, содержащую строковое представление числа в указанной системе счисления, в эквивалентное беззнаковое 16-битное целое. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 16-битное целое с использованием предоставленной информации о форматировании. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 16-битное целое с использованием предоставленной информации о форматировании и стиле числа. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)([Enum](../enum/)) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное упакованное значение в эквивалентное беззнаковое 16-битное целое. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**bool**) | Преобразует указанное логическое значение в эквивалентное 32-битное беззнаковое целое. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint8_t**) | Преобразует указанное 8-битное беззнаковое целое в эквивалентное 32-битное беззнаковое целое. |
| static **uint32_t** [ToUInt32](./touint32/)(**int8_t**) | Преобразует указанное 8-битное знаковое целое в эквивалентное 32-битное беззнаковое целое. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint16_t**) | Преобразует указанное 16-битное беззнаковое целое в эквивалентное 32-битное беззнаковое целое. |
| static **uint32_t** [ToUInt32](./touint32/)(**int16_t**) | Преобразует указанное 16-битное знаковое целое в эквивалентное 32-битное беззнаковое целое. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint32_t**) | Возвращает указанное 32-битное беззнаковое целое. |
| static **uint32_t** [ToUInt32](./touint32/)(**int32_t**) | Преобразует указанное 32-битное знаковое целое в эквивалентное 32-битное беззнаковое целое. |
| static **uint32_t** [ToUInt32](./touint32/)(**uint64_t**) | Преобразует указанное 64-битное беззнаковое целое в эквивалентное 32-битное беззнаковое целое. |
| static **uint32_t** [ToUInt32](./touint32/)(**int64_t**) | Преобразует указанное 64-битное знаковое целое в эквивалентное 32-битное беззнаковое целое. |
| static **uint32_t** [ToUInt32](./touint32/)(**float**) | Преобразует указанное число типа float в эквивалентное 32-битное беззнаковое целое. |
| static **uint32_t** [ToUInt32](./touint32/)(**double**) | Преобразует указанное число типа double в эквивалентное 32-битное беззнаковое целое. |
| static **uint32_t** [ToUInt32](./touint32/)(const [Decimal](../decimal/)\&) | Преобразует указанное десятичное число в эквивалентное 32-битное беззнаковое целое. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(char_t) | Преобразует указанный символ Unicode в эквивалентное 32-битное беззнаковое целое. |
| static **uint32_t** [ToUInt32](./touint32/)([DateTime](../datetime/)) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(std::nullptr_t) | Преобразует указанную нулевую строку в эквивалентное беззнаковое 32-битное целое. |
| static **uint32_t** [ToUInt32](./touint32/)(const char_t *) | Преобразует указанную C-строку, содержащую строковое представление числа, в эквивалентное беззнаковое 32-битное целое. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 32-битное целое. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, int) | Преобразует указанную строку, содержащую строковое представление числа в указанной системе счисления, в эквивалентное беззнаковое 32-битное целое. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 32-битное целое с использованием предоставленной информации о форматировании. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 32-битное целое с использованием предоставленной информации о форматировании и стиле числа. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)([Enum](../enum/)) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное упакованное значение в эквивалентное беззнаковое 32-битное целое. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**bool**) | Преобразует указанное логическое значение в эквивалентное 64-битное беззнаковое целое. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint8_t**) | Преобразует указанное 8-битное беззнаковое целое в эквивалентное 64-битное беззнаковое целое. |
| static **uint64_t** [ToUInt64](./touint64/)(**int8_t**) | Преобразует указанное 8-битное знаковое целое в эквивалентное 64-битное беззнаковое целое. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint16_t**) | Преобразует указанное 16-битное беззнаковое целое в эквивалентное 64-битное беззнаковое целое. |
| static **uint64_t** [ToUInt64](./touint64/)(**int16_t**) | Преобразует указанное 16-битное знаковое целое в эквивалентное 64-битное беззнаковое целое. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint32_t**) | Преобразует указанное 32-битное беззнаковое целое в эквивалентное 64-битное беззнаковое целое. |
| static **uint64_t** [ToUInt64](./touint64/)(**int32_t**) | Преобразует указанное 32-битное знаковое целое в эквивалентное 64-битное беззнаковое целое. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint64_t**) | Возвращает указанное 64-битное беззнаковое целое. |
| static **uint64_t** [ToUInt64](./touint64/)(**int64_t**) | Преобразует указанное 64-битное знаковое целое в эквивалентное 64-битное беззнаковое целое. |
| static **uint64_t** [ToUInt64](./touint64/)(**float**) | Преобразует указанное число типа float в эквивалентное 64-битное беззнаковое целое. |
| static **uint64_t** [ToUInt64](./touint64/)(**double**) | Преобразует указанное число типа double в эквивалентное 64-битное беззнаковое целое. |
| static **uint64_t** [ToUInt64](./touint64/)(const [Decimal](../decimal/)\&) | Преобразует указанное десятичное число в эквивалентное 64-битное беззнаковое целое. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(char_t) | Преобразует указанный символ Unicode в эквивалентное 64-битное беззнаковое целое. |
| static **uint64_t** [ToUInt64](./touint64/)([DateTime](../datetime/)) | Преобразование не поддерживается. Всегда генерирует InvalidCastException. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(std::nullptr_t) | Преобразует указанную нулевую строку в эквивалентное беззнаковое 64-битное целое. |
| static **uint64_t** [ToUInt64](./touint64/)(const char_t *) | Преобразует указанную C-строку, содержащую строковое представление числа, в эквивалентное беззнаковое 64-битное целое. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 64-битное целое. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, int) | Преобразует указанную строку, содержащую строковое представление числа в указанной системе счисления, в эквивалентное беззнаковое 64-битное целое. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 64-битное целое с использованием предоставленной информации о форматировании. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное беззнаковое 64-битное целое с использованием предоставленной информации о форматировании и стиле числа. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)([Enum](../enum/)) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует указанное упакованное значение в эквивалентное беззнаковое 64-битное целое. |
## Смотрите также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)