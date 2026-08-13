---
title: Convert
second_title: Aspose.Slides for C++ API 레퍼런스
description: "한 유형의 값을 다른 유형의 값으로 변환하는 메서드를 포함하는 구조체입니다. 이 유형은 스택에 할당하고 값 또는 참조로 함수에 전달해야 합니다. 이 유형의 객체를 관리하기 위해 System::SmartPtr 클래스를 사용하지 마십시오."
type: docs
weight: 1561
url: /ko/system/convert/
---
## 변환 구조체

한 유형의 값을 다른 유형의 값으로 변환하는 메서드를 포함하는 구조체입니다. 이 유형은 스택에 할당되고 값 또는 참조로 함수에 전달되어야 합니다. [System::SmartPtr](../smartptr/) 클래스를 사용하여 이 유형의 객체를 관리하지 마십시오.

```cpp
class Convert
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&) | 구현되지 않음. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64CharArray](./frombase64chararray/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Unicode 문자 배열의 범위로 표현된 base-64 인코딩 데이터를 디코딩합니다. |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64String](./frombase64string/)(const [String](../string/)\&) | 문자열로 표현된 base-64 인코딩 데이터를 디코딩합니다. |
| static [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | 지정된 박싱된 값의 유형을 나타내는 TypeCode 값을 반환합니다. |
| static std::enable_if_t<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\> [IsDBNull](./isdbnull/)(const T\&) | 구현되지 않음. |
| static **bool** [IsDBNull](./isdbnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 구현되지 않음 가짜 구현으로, 값이 nullptr인지 확인합니다. |
| static Target [To](./to/)(const Source\&) |  |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, **bool**) | 지정된 바이트 배열의 요소 범위를 base-64 인코딩하고, 인코딩된 데이터를 Unicode 문자 배열로 저장합니다. |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, [Base64FormattingOptions](../base64formattingoptions/)) | 지정된 바이트 배열의 요소 범위를 base-64 인코딩하고, 인코딩된 데이터를 Unicode 문자 배열로 저장합니다. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**) | 지정된 바이트 배열의 요소를 base-64 인코딩하고, 인코딩된 데이터를 문자열로 반환합니다. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, **bool**) | 지정된 바이트 배열의 요소 범위를 base-64 인코딩하고, 인코딩된 데이터를 문자열로 반환합니다. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, [Base64FormattingOptions](../base64formattingoptions/)) | 지정된 바이트 배열의 요소를 base-64 인코딩하고, 인코딩된 데이터를 문자열로 반환합니다. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, [Base64FormattingOptions](../base64formattingoptions/)) | 지정된 바이트 배열의 요소 범위를 base-64 인코딩하고, 인코딩된 데이터를 문자열로 반환합니다. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**bool**) | 지정된 부울 값을 반환합니다. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint8_t**) | 지정된 8비트 부호 없는 정수를 동등한 부울 값으로 변환합니다. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int8_t**) | 지정된 8비트 부호 있는 정수를 동등한 부울 값으로 변환합니다. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint16_t**) | 지정된 16비트 부호 없는 정수를 동등한 부울 값으로 변환합니다. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int16_t**) | 지정된 16비트 부호 있는 정수를 동등한 부울 값으로 변환합니다. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint32_t**) | 지정된 32비트 부호 없는 정수를 동등한 부울 값으로 변환합니다. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int32_t**) | 지정된 32비트 부호 있는 정수를 동등한 부울 값으로 변환합니다. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint64_t**) | 지정된 64비트 부호 없는 정수를 동등한 부울 값으로 변환합니다. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int64_t**) | 지정된 64비트 부호 있는 정수를 동등한 부울 값으로 변환합니다. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**float**) | 지정된 부동 소수점 값을 동등한 부울 값으로 변환합니다. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**double**) | 지정된 부동 소수점 값을 동등한 부울 값으로 변환합니다. |
| static **bool** [ToBoolean](./toboolean/)(const [Decimal](../decimal/)\&) | 지정된 10진수 값을 동등한 부울 값으로 변환합니다. |
| static **bool** [ToBoolean](./toboolean/)(char_t) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static **bool** [ToBoolean](./toboolean/)([DateTime](../datetime/)) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static constexpr **bool** [ToBoolean](./toboolean/)(std::nullptr_t) | 지정된 null 문자열을 동등한 부울 값으로 변환합니다. |
| static **bool** [ToBoolean](./toboolean/)(const char_t *) | 지정된 C 문자열을 bool 타입 값으로 변환합니다. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&) | 지정된 문자열을 bool 타입 값으로 변환합니다. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 문자열을 bool 타입 값으로 변환합니다. |
| static **bool** [ToBoolean](./toboolean/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 박싱된 값을 동등한 부울 값으로 변환합니다. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**bool**) | 지정된 부울 값을 동등한 8비트 부호 없는 정수로 변환합니다. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**uint8_t**) | 지정된 8비트 부호 없는 정수를 반환합니다. |
| static **uint8_t** [ToByte](./tobyte/)(**int8_t**) | 지정된 8비트 부호 있는 정수를 동등한 8비트 부호 없는 정수로 변환합니다. |
| static **uint8_t** [ToByte](./tobyte/)(**uint16_t**) | 지정된 16비트 부호 없는 정수를 동등한 8비트 부호 없는 정수로 변환합니다. |
| static **uint8_t** [ToByte](./tobyte/)(**int16_t**) | 지정된 16비트 부호 있는 정수를 동등한 8비트 부호 없는 정수로 변환합니다. |
| static **uint8_t** [ToByte](./tobyte/)(**uint32_t**) | 지정된 32비트 부호 없는 정수를 동등한 8비트 부호 없는 정수로 변환합니다. |
| static **uint8_t** [ToByte](./tobyte/)(**int32_t**) | 지정된 32비트 부호 있는 정수를 동등한 8비트 부호 없는 정수로 변환합니다. |
| static **uint8_t** [ToByte](./tobyte/)(**uint64_t**) | 지정된 64비트 부호 없는 정수를 동등한 8비트 부호 없는 정수로 변환합니다. |
| static **uint8_t** [ToByte](./tobyte/)(**int64_t**) | 지정된 64비트 부호 있는 정수를 동등한 8비트 부호 없는 정수로 변환합니다. |
| static **uint8_t** [ToByte](./tobyte/)(**float**) | 지정된 부동 소수점 값을 동등한 8비트 부호 없는 정수로 변환합니다. |
| static **uint8_t** [ToByte](./tobyte/)(**double**) | 지정된 부동 소수점 값을 동등한 8비트 부호 없는 정수로 변환합니다. |
| static **uint8_t** [ToByte](./tobyte/)(const [Decimal](../decimal/)\&) | 지정된 10진수 값을 동등한 8비트 부호 없는 정수로 변환합니다. |
| static **uint8_t** [ToByte](./tobyte/)(char_t) | 지정된 유니코드 문자를 동등한 8비트 부호 없는 정수로 변환합니다. |
| static **uint8_t** [ToByte](./tobyte/)([DateTime](../datetime/)) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(std::nullptr_t) | 지정된 null 문자열을 동등한 부호 없는 8비트 정수 값으로 변환합니다. |
| static **uint8_t** [ToByte](./tobyte/)(const char_t *) | 숫자 문자열 표현을 포함하는 C 문자열을 동등한 부호 없는 8비트 정수 값으로 변환합니다. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&) | 숫자 문자열 표현을 포함하는 문자열을 동등한 부호 없는 8비트 정수 값으로 변환합니다. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, int) | 지정된 진법의 숫자 문자열 표현을 포함하는 문자열을 동등한 부호 없는 8비트 정수 값으로 변환합니다. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 서식 정보를 사용하여 숫자 문자열 표현을 포함하는 문자열을 동등한 부호 없는 8비트 정수 값으로 변환합니다. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 서식 정보와 숫자 스타일을 사용하여 숫자 문자열 표현을 포함하는 문자열을 동등한 부호 없는 8비트 정수 값으로 변환합니다. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)([Enum](../enum/)) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 박싱된 값을 동등한 부호 없는 8비트 정수 값으로 변환합니다. |
| static char_t [ToChar](./tochar/)(**bool**) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static constexpr char_t [ToChar](./tochar/)(**uint8_t**) | 지정된 8비트 부호 없는 정수를 동등한 유니코드 문자로 변환합니다. |
| static char_t [ToChar](./tochar/)(**int8_t**) | 지정된 8비트 부호 있는 정수를 동등한 유니코드 문자로 변환합니다. |
| static constexpr char_t [ToChar](./tochar/)(**uint16_t**) | 지정된 16비트 부호 없는 정수를 동등한 유니코드 문자로 변환합니다. |
| static char_t [ToChar](./tochar/)(**int16_t**) | 지정된 16비트 부호 있는 정수를 동등한 유니코드 문자로 변환합니다. |
| static char_t [ToChar](./tochar/)(**uint32_t**) | 지정된 32비트 부호 없는 정수를 동등한 유니코드 문자로 변환합니다. |
| static char_t [ToChar](./tochar/)(**int32_t**) | 지정된 32비트 부호 있는 정수를 동등한 유니코드 문자로 변환합니다. |
| static char_t [ToChar](./tochar/)(**uint64_t**) | 지정된 64비트 부호 없는 정수를 동등한 유니코드 문자로 변환합니다. |
| static char_t [ToChar](./tochar/)(**int64_t**) | 지정된 64비트 부호 있는 정수를 동등한 유니코드 문자로 변환합니다. |
| static char_t [ToChar](./tochar/)(**float**) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static char_t [ToChar](./tochar/)(**double**) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static char_t [ToChar](./tochar/)(const [Decimal](../decimal/)\&) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static constexpr char_t [ToChar](./tochar/)(char_t) | 지정된 유니코드 문자를 반환합니다. |
| static char_t [ToChar](./tochar/)([DateTime](../datetime/)) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static char_t [ToChar](./tochar/)(const char_t *) | 지정된 C 문자열의 첫 번째이자 유일한 문자를 char_t 값으로 변환합니다. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&) | 지정된 문자열의 첫 번째이자 유일한 문자를 char_t 값으로 변환합니다. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 문자열의 첫 번째이자 유일한 문자를 char_t 값으로 변환합니다. |
| static char_t [ToChar](./tochar/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 박싱된 값을 동등한 유니코드 문자로 변환합니다. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**bool**) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint8_t**) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int8_t**) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint16_t**) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int16_t**) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint32_t**) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int32_t**) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint64_t**) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int64_t**) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**float**) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**double**) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [Decimal](../decimal/)\&) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(char_t) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static constexpr [DateTime](../datetime/) [ToDateTime](./todatetime/)([DateTime](../datetime/)) | 지정된 날짜와 시간을 반환합니다. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&) | 지정된 문자열을 [DateTime](../datetime/) 클래스의 인스턴스로 변환합니다. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 서식 정보를 사용하여 지정된 문자열을 [DateTime](../datetime/) 클래스의 인스턴스로 변환합니다. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 박싱된 값을 동등한 [DateTime](../datetime/) 값으로 변환합니다. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**bool**) | 지정된 부울 값을 동등한 십진수로 변환합니다. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint8_t**) | 지정된 8비트 부호 없는 정수를 동등한 십진수로 변환합니다. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int8_t**) | 지정된 8비트 부호 있는 정수를 동등한 십진수로 변환합니다. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint16_t**) | 지정된 16비트 부호 없는 정수를 동등한 십진수로 변환합니다. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int16_t**) | 지정된 16비트 부호 있는 정수를 동등한 십진수로 변환합니다. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint32_t**) | 지정된 32비트 부호 없는 정수를 동등한 십진수로 변환합니다. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int32_t**) | 지정된 32비트 부호 있는 정수를 동등한 십진수로 변환합니다. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint64_t**) | 지정된 64비트 부호 없는 정수를 동등한 십진수로 변환합니다. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int64_t**) | 지정된 64비트 부호 있는 정수를 동등한 십진수로 변환합니다. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**float**) | 지정된 float 숫자를 동등한 십진수로 변환합니다. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**double**) | 지정된 double 숫자를 동등한 십진수로 변환합니다. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [Decimal](../decimal/)\&) | 지정된 십진수를 반환합니다. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(char_t) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)([DateTime](../datetime/)) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(std::nullptr_t) | 지정된 null 문자열을 동등한 [Decimal](../decimal/) 값으로 변환합니다. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const char_t *) | 숫자의 문자열 표현을 포함한 지정된 C 문자열을 동등한 [Decimal](../decimal/) 값으로 변환합니다. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&) | 숫자의 문자열 표현을 포함한 지정된 문자열을 동등한 [Decimal](../decimal/) 값으로 변환합니다. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 서식 정보를 사용하여 숫자의 문자열 표현을 포함한 지정된 문자열을 동등한 [Decimal](../decimal/) 값으로 변환합니다. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 숫자 스타일 및 서식 정보를 사용하여 숫자의 문자열 표현을 포함한 지정된 문자열을 동등한 [Decimal](../decimal/) 값으로 변환합니다. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 박싱된 값을 동등한 [Decimal](../decimal/) 값으로 변환합니다. |
| static constexpr **double** [ToDouble](./todouble/)(**bool**) | 지정된 부울 값을 동등한 배정밀도 부동소수점 수로 변환합니다. |
| static constexpr **double** [ToDouble](./todouble/)(**uint8_t**) | 지정된 8비트 부호 없는 정수를 동등한 배정밀도 부동소수점 수로 변환합니다. |
| static constexpr **double** [ToDouble](./todouble/)(**int8_t**) | 지정된 8비트 부호 있는 정수를 동등한 배정밀도 부동소수점 수로 변환합니다. |
| static constexpr **double** [ToDouble](./todouble/)(**uint16_t**) | 지정된 16비트 부호 없는 정수를 동등한 배정밀도 부동소수점 수로 변환합니다. |
| static constexpr **double** [ToDouble](./todouble/)(**int16_t**) | 지정된 16비트 부호 있는 정수를 동등한 배정밀도 부동소수점 수로 변환합니다. |
| static constexpr **double** [ToDouble](./todouble/)(**uint32_t**) | 지정된 32비트 부호 없는 정수를 동등한 배정밀도 부동소수점 수로 변환합니다. |
| static constexpr **double** [ToDouble](./todouble/)(**int32_t**) | 지정된 32비트 부호 있는 정수를 동등한 배정밀도 부동소수점 수로 변환합니다. |
| static constexpr **double** [ToDouble](./todouble/)(**uint64_t**) | 지정된 64비트 부호 없는 정수를 동등한 배정밀도 부동소수점 수로 변환합니다. |
| static constexpr **double** [ToDouble](./todouble/)(**int64_t**) | 지정된 64비트 부호 있는 정수를 동등한 배정밀도 부동소수점 수로 변환합니다. |
| static constexpr **double** [ToDouble](./todouble/)(**float**) | 지정된 단정밀도 수를 동등한 배정밀도 부동소수점 수로 변환합니다. |
| static constexpr **double** [ToDouble](./todouble/)(**double**) | 지정된 double 숫자를 반환합니다. |
| static **double** [ToDouble](./todouble/)(const [Decimal](../decimal/)\&) | 지정된 십진수를 동등한 배정밀도 부동소수점 수로 변환합니다. |
| static **double** [ToDouble](./todouble/)(char_t) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static **double** [ToDouble](./todouble/)([DateTime](../datetime/)) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static constexpr **double** [ToDouble](./todouble/)(std::nullptr_t) | 지정된 null 문자열을 동등한 배정밀도 부동소수점 값으로 변환합니다. |
| static **double** [ToDouble](./todouble/)(const char_t *) | 숫자의 문자열 표현을 포함한 지정된 C 문자열을 동등한 배정밀도 부동소수점 값으로 변환합니다. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&) | 숫자의 문자열 표현을 포함한 지정된 문자열을 동등한 배정밀도 부동소수점 값으로 변환합니다. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 서식 정보를 사용하여 숫자의 문자열 표현을 포함한 지정된 문자열을 동등한 배정밀도 부동소수점 값으로 변환합니다. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 서식 정보와 숫자 스타일을 사용하여 숫자의 문자열 표현을 포함한 지정된 문자열을 동등한 배정밀도 부동소수점 값으로 변환합니다. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 박싱된 값을 배정밀도 부동소수점 값으로 변환합니다. 박싱된 값의 유형이 [String](../string/)인 경우 변환 중에 지정된 문자열 형식이 사용됩니다. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**bool**) | 지정된 부울 값을 동등한 16비트 부호 있는 정수로 변환합니다. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**uint8_t**) | 지정된 8비트 부호 없는 정수를 동등한 16비트 부호 있는 정수로 변환합니다. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int8_t**) | 지정된 8비트 부호 있는 정수를 동등한 16비트 부호 있는 정수로 변환합니다. |
| static **int16_t** [ToInt16](./toint16/)(**uint16_t**) | 지정된 16비트 부호 없는 정수를 동등한 16비트 부호 있는 정수로 변환합니다. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int16_t**) | 지정된 16비트 부호 있는 정수를 반환합니다. |
| static **int16_t** [ToInt16](./toint16/)(**uint32_t**) | 지정된 32비트 부호 없는 정수를 동등한 16비트 부호 있는 정수로 변환합니다. |
| static **int16_t** [ToInt16](./toint16/)(**int32_t**) | 지정된 32비트 부호 있는 정수를 동등한 16비트 부호 있는 정수로 변환합니다. |
| static **int16_t** [ToInt16](./toint16/)(**uint64_t**) | 지정된 64비트 부호 없는 정수를 동등한 16비트 부호 있는 정수로 변환합니다. |
| static **int16_t** [ToInt16](./toint16/)(**int64_t**) | 지정된 64비트 부호 있는 정수를 동등한 16비트 부호 있는 정수로 변환합니다. |
| static **int16_t** [ToInt16](./toint16/)(**float**) | 지정된 float 숫자를 동등한 16비트 부호 있는 정수로 변환합니다. |
| static **int16_t** [ToInt16](./toint16/)(**double**) | 지정된 double 숫자를 동등한 16비트 부호 있는 정수로 변환합니다. |
| static **int16_t** [ToInt16](./toint16/)(const [Decimal](../decimal/)\&) | 지정된 십진수를 동등한 16비트 부호 있는 정수로 변환합니다. |
| static **int16_t** [ToInt16](./toint16/)(char_t) | 지정된 유니코드 문자를 동등한 16비트 부호 있는 정수로 변환합니다. |
| static **int16_t** [ToInt16](./toint16/)([DateTime](../datetime/)) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static constexpr **int16_t** [ToInt16](./toint16/)(std::nullptr_t) | 지정된 null 문자열을 동등한 16비트 정수 값으로 변환합니다. |
| static **int16_t** [ToInt16](./toint16/)(const char_t *) | 숫자의 문자열 표현을 포함한 지정된 C 문자열을 동등한 16비트 정수 값으로 변환합니다. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&) | 숫자의 문자열 표현을 포함한 지정된 문자열을 동등한 16비트 정수 값으로 변환합니다. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, int) | 지정된 진법으로 숫자의 문자열 표현을 포함한 지정된 문자열을 동등한 16비트 정수 값으로 변환합니다. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 서식 정보를 사용하여 숫자의 문자열 표현을 포함한 지정된 문자열을 동등한 16비트 정수 값으로 변환합니다. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16t** [ToInt16](./toint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 서식 정보와 숫자 스타일을 사용하여 숫자의 문자열 표현을 포함한 지정된 문자열을 동등한 16비트 정수 값으로 변환합니다. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)([Enum](../enum/)) |  |
| static **int16_t** [ToInt16](./toint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 박싱된 값을 동등한 16비트 정수 값으로 변환합니다. |
| static constexpr int [ToInt32](./toint32/)(**bool**) | 지정된 부울 값을 동등한 32비트 부호 있는 정수로 변환합니다. |
| static constexpr int [ToInt32](./toint32/)(**uint8_t**) | 지정된 8비트 부호 없는 정수를 동등한 32비트 부호 있는 정수로 변환합니다. |
| static constexpr int [ToInt32](./toint32/)(**int8_t**) | 지정된 8비트 부호 있는 정수를 동등한 32비트 부호 있는 정수로 변환합니다. |
| static constexpr int [ToInt32](./toint32/)(**uint16_t**) | 지정된 16비트 부호 없는 정수를 동등한 32비트 부호 있는 정수로 변환합니다. |
| static constexpr int [ToInt32](./toint32/)(**int16_t**) | 지정된 16비트 부호 있는 정수를 동등한 32비트 부호 있는 정수로 변환합니다. |
| static int [ToInt32](./toint32/)(**uint32_t**) | 지정된 32비트 부호 없는 정수를 동등한 32비트 부호 있는 정수로 변환합니다. |
| static constexpr int [ToInt32](./toint32/)(**int32_t**) | 지정된 32비트 부호 있는 정수를 반환합니다. |
| static int [ToInt32](./toint32/)(**uint64_t**) | 지정된 64비트 부호 없는 정수를 동등한 32비트 부호 있는 정수로 변환합니다. |
| static int [ToInt32](./toint32/)(**int64_t**) | 지정된 64비트 부호 있는 정수를 동등한 32비트 부호 있는 정수로 변환합니다. |
| static int [ToInt32](./toint32/)(**float**) | 지정된 부동소수점(float) 숫자를 동등한 32비트 부호 있는 정수로 변환합니다. |
| static int [ToInt32](./toint32/)(**double**) | 지정된 double 숫자를 동등한 32비트 부호 있는 정수로 변환합니다. |
| static int [ToInt32](./toint32/)(const [Decimal](../decimal/)\&) | 지정된 소수(decimal) 숫자를 동등한 32비트 부호 있는 정수로 변환합니다. |
| static constexpr int [ToInt32](./toint32/)(char_t) | 지정된 유니코드 문자를 동등한 32비트 부호 있는 정수로 변환합니다. |
| static int [ToInt32](./toint32/)([DateTime](../datetime/)) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static constexpr int [ToInt32](./toint32/)(std::nullptr_t) | 지정된 null 문자열을 동등한 32비트 정수 값으로 변환합니다. |
| static int [ToInt32](./toint32/)(const char_t *) | 숫자의 문자열 표현을 포함하는 지정된 C 문자열을 동등한 32비트 정수 값으로 변환합니다. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&) | 지정된 문자열(숫자 표현 포함)을 동등한 32비트 정수 값으로 변환합니다. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, int) | 지정된 진법의 숫자 문자열을 동등한 32비트 정수 값으로 변환합니다. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 서식 정보를 사용하여 숫자 문자열을 동등한 32비트 정수 값으로 변환합니다. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 서식 정보와 숫자 형식을 사용하여 문자열을 동등한 32비트 정수 값으로 변환합니다. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [ToInt32](./toint32/)([Enum](../enum/)) |  |
| static int [ToInt32](./toint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 박싱된 값을 동등한 32비트 정수 값으로 변환합니다. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**bool**) | 지정된 부울 값을 동등한 64비트 부호 있는 정수로 변환합니다. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint8_t**) | 지정된 8비트 부호 없는 정수를 동등한 64비트 부호 있는 정수로 변환합니다. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int8_t**) | 지정된 8비트 부호 있는 정수를 동등한 64비트 부호 있는 정수로 변환합니다. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint16_t**) | 지정된 16비트 부호 없는 정수를 동등한 64비트 부호 있는 정수로 변환합니다. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int16_t**) | 지정된 16비트 부호 있는 정수를 동등한 64비트 부호 있는 정수로 변환합니다. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint32_t**) | 지정된 32비트 부호 없는 정수를 동등한 64비트 부호 있는 정수로 변환합니다. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int32_t**) | 지정된 32비트 부호 있는 정수를 동등한 64비트 부호 있는 정수로 변환합니다. |
| static **int64_t** [ToInt64](./toint64/)(**uint64_t**) | 지정된 64비트 부호 없는 정수를 동등한 64비트 부호 있는 정수로 변환합니다. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int64_t**) | 지정된 64비트 부호 있는 정수를 반환합니다. |
| static **int64_t** [ToInt64](./toint64/)(**float**) | 지정된 부동소수점(float) 숫자를 동등한 64비트 부호 있는 정수로 변환합니다. |
| static **int64_t** [ToInt64](./toint64/)(**double**) | 지정된 double 숫자를 동등한 64비트 부호 있는 정수로 변환합니다. |
| static **int64_t** [ToInt64](./toint64/)(const [Decimal](../decimal/)\&) | 지정된 소수(decimal) 숫자를 동등한 64비트 부호 있는 정수로 변환합니다. |
| static constexpr **int64_t** [ToInt64](./toint64/)(char_t) | 지정된 유니코드 문자를 동등한 64비트 부호 있는 정수로 변환합니다. |
| static **int64_t** [ToInt64](./toint64/)([DateTime](../datetime/)) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static constexpr **int64_t** [ToInt64](./toint64/)(std::nullptr_t) | 지정된 null 문자열을 동등한 64비트 정수 값으로 변환합니다. |
| static **int64_t** [ToInt64](./toint64/)(const char_t *) | 숫자의 문자열 표현을 포함하는 지정된 C 문자열을 동등한 64비트 정수 값으로 변환합니다. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&) | 지정된 문자열(숫자 표현 포함)을 동등한 64비트 정수 값으로 변환합니다. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, int) | 지정된 진법의 숫자 문자열을 동등한 64비트 정수 값으로 변환합니다. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 서식 정보를 사용하여 숫자 문자열을 동등한 64비트 정수 값으로 변환합니다. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 서식 정보와 숫자 형식을 사용하여 문자열을 동등한 64비트 정수 값으로 변환합니다. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)([Enum](../enum/)) |  |
| static **int64_t** [ToInt64](./toint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 박싱된 값을 동등한 64비트 정수 값으로 변환합니다. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**bool**) | 지정된 부울 값을 동등한 8비트 부호 있는 정수로 변환합니다. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint8_t**) | 지정된 8비트 부호 없는 정수를 동등한 8비트 부호 있는 정수로 변환합니다. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**int8_t**) | 지정된 8비트 부호 있는 정수를 반환합니다. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint16_t**) | 지정된 16비트 부호 없는 정수를 동등한 8비트 부호 있는 정수로 변환합니다. |
| static **int8_t** [ToSByte](./tosbyte/)(**int16_t**) | 지정된 16비트 부호 있는 정수를 동등한 8비트 부호 있는 정수로 변환합니다. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint32_t**) | 지정된 32비트 부호 없는 정수를 동등한 8비트 부호 있는 정수로 변환합니다. |
| static **int8_t** [ToSByte](./tosbyte/)(**int32_t**) | 지정된 32비트 부호 있는 정수를 동등한 8비트 부호 있는 정수로 변환합니다. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint64_t**) | 지정된 64비트 부호 없는 정수를 동등한 8비트 부호 있는 정수로 변환합니다. |
| static **int8_t** [ToSByte](./tosbyte/)(**int64_t**) | 지정된 64비트 부호 있는 정수를 동등한 8비트 부호 있는 정수로 변환합니다. |
| static **int8_t** [ToSByte](./tosbyte/)(**float**) | 지정된 부동소수점(float) 숫자를 동등한 8비트 부호 있는 정수로 변환합니다. |
| static **int8_t** [ToSByte](./tosbyte/)(**double**) | 지정된 double 숫자를 동등한 8비트 부호 있는 정수로 변환합니다. |
| static **int8_t** [ToSByte](./tosbyte/)(const [Decimal](../decimal/)\&) | 지정된 소수(decimal) 숫자를 동등한 8비트 부호 있는 정수로 변환합니다. |
| static **int8_t** [ToSByte](./tosbyte/)(char_t) | 지정된 유니코드 문자를 동등한 8비트 부호 있는 정수로 변환합니다. |
| static **int8_t** [ToSByte](./tosbyte/)([DateTime](../datetime/)) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(std::nullptr_t) | 지정된 null 문자열을 동등한 8비트 정수 값으로 변환합니다. |
| static **int8_t** [ToSByte](./tosbyte/)(const char_t *) | 숫자의 문자열 표현을 포함하는 지정된 C 문자열을 동등한 8비트 정수 값으로 변환합니다. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&) | 지정된 문자열(숫자 표현 포함)을 동등한 8비트 정수 값으로 변환합니다. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, int) | 지정된 진법의 숫자 문자열을 동등한 8비트 정수 값으로 변환합니다. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 서식 정보를 사용하여 문자열을 동등한 부호 없는 8비트 정수 값으로 변환합니다. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 서식 정보와 숫자 형식을 사용하여 문자열을 동등한 8비트 정수 값으로 변환합니다. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)([Enum](../enum/)) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 박싱된 값을 동등한 8비트 정수 값으로 변환합니다. |
| static constexpr **float** [ToSingle](./tosingle/)(**bool**) | 지정된 부울 값을 동등한 단정밀도 부동소수점 숫자로 변환합니다. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint8_t**) | 지정된 8비트 부호 없는 정수를 동등한 단정밀도 부동소수점 숫자로 변환합니다. |
| static constexpr **float** [ToSingle](./tosingle/)(**int8_t**) | 지정된 8비트 부호 있는 정수를 동등한 단정밀도 부동소수점 숫자로 변환합니다. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint16_t**) | 지정된 16비트 부호 없는 정수를 동등한 단정밀도 부동소수점 숫자로 변환합니다. |
| static constexpr **float** [ToSingle](./tosingle/)(**int16_t**) | 지정된 16비트 부호 있는 정수를 동등한 단정밀도 부동소수점 숫자로 변환합니다. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint32_t**) | 지정된 32비트 부호 없는 정수를 동등한 단정밀도 부동소수점 숫자로 변환합니다. |
| static constexpr **float** [ToSingle](./tosingle/)(**int32_t**) | 지정된 32비트 부호 있는 정수를 동등한 단정밀도 부동소수점 숫자로 변환합니다. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint64_t**) | 지정된 64비트 부호 없는 정수를 동등한 단정도 부동소수점 숫자로 변환합니다. |
| static constexpr **float** [ToSingle](./tosingle/)(**int64_t**) | 지정된 64비트 부호 있는 정수를 동등한 단정도 부동소수점 숫자로 변환합니다. |
| static constexpr **float** [ToSingle](./tosingle/)(**float**) | 지정된 float 값을 반환합니다. |
| static constexpr **float** [ToSingle](./tosingle/)(**double**) | 지정된 double 정밀도 숫자를 동등한 단정도 부동소수점 숫자로 변환합니다. |
| static **float** [ToSingle](./tosingle/)(const [Decimal](../decimal/)\&) | 지정된 소수 숫자를 동등한 단정도 부동소수점 숫자로 변환합니다. |
| static **float** [ToSingle](./tosingle/)(char_t) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static **float** [ToSingle](./tosingle/)([DateTime](../datetime/)) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static constexpr **float** [ToSingle](./tosingle/)(std::nullptr_t) | 지정된 null 문자열을 동등한 단정도 부동소수점 값으로 변환합니다. |
| static **float** [ToSingle](./tosingle/)(const char_t *) | 숫자의 문자열 표현을 포함하는 지정된 c 문자열을 동등한 단정도 부동소수점 값으로 변환합니다. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&) | 숫자의 문자열 표현을 포함하는 지정된 문자열을 동등한 단정도 부동소수점 값으로 변환합니다. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 서식 정보를 사용하여 숫자의 문자열 표현을 포함하는 지정된 문자열을 동등한 단정도 부동소수점 값으로 변환합니다. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 서식 정보와 숫자 스타일을 사용하여 숫자의 문자열 표현을 포함하는 지정된 문자열을 동등한 단정도 부동소수점 값으로 변환합니다. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 박싱된 값을 단정도 부동소수점 값으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**) | 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**) | 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**) | 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**) | 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**) | 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**) | 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**) | 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**) | 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**float**) | 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**double**) | 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&) | 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/)) | 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 문화별 서식 정보를 사용하여 지정된 값을 문자열로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 문화별 서식 정보를 사용하여 지정된 값을 문자열로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 문화별 서식 정보를 사용하여 지정된 값을 문자열로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 문화별 서식 정보를 사용하여 지정된 값을 문자열로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 문화별 서식 정보를 사용하여 지정된 값을 문자열로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 문화별 서식 정보를 사용하여 지정된 값을 문자열로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 문화별 서식 정보를 사용하여 지정된 값을 문자열로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 문화별 서식 정보를 사용하여 지정된 값을 문자열로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 문화별 서식 정보를 사용하여 지정된 값을 문자열로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 문화별 서식 정보를 사용하여 지정된 값을 문자열로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 문화별 서식 정보를 사용하여 지정된 값을 문자열로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 문화별 서식 정보를 사용하여 지정된 값을 문자열로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 [IFormatProvider](../iformatprovider/) 객체가 제공하는 지정된 문자열 형식 및 문화별 서식 정보를 사용하여 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 [IFormatProvider](../iformatprovider/) 객체가 제공하는 지정된 문자열 형식 및 문화별 서식 정보를 사용하여 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 [IFormatProvider](../iformatprovider/) 객체가 제공하는 지정된 문자열 형식 및 문화별 서식 정보를 사용하여 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 [IFormatProvider](../iformatprovider/) 객체가 제공하는 지정된 문자열 형식 및 문화별 서식 정보를 사용하여 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 [IFormatProvider](../iformatprovider/) 객체가 제공하는 지정된 문자열 형식 및 문화별 서식 정보를 사용하여 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 [IFormatProvider](../iformatprovider/) 객체가 제공하는 지정된 문자열 형식 및 문화별 서식 정보를 사용하여 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 값을 지정된 문자열 형식 및 지정된 [IFormatProvider](../iformatprovider/) 객체가 제공하는 문화별 형식 정보를 사용하여 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 값을 지정된 문자열 형식 및 지정된 [IFormatProvider](../iformatprovider/) 객체가 제공하는 문화별 형식 정보를 사용하여 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 값을 지정된 문자열 형식 및 지정된 [IFormatProvider](../iformatprovider/) 객체가 제공하는 문화별 형식 정보를 사용하여 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 값을 지정된 문자열 형식 및 지정된 [IFormatProvider](../iformatprovider/) 객체가 제공하는 문화별 형식 정보를 사용하여 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 값을 지정된 문자열 형식 및 지정된 [IFormatProvider](../iformatprovider/) 객체가 제공하는 문화별 형식 정보를 사용하여 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 값을 지정된 문자열 형식 및 지정된 [IFormatProvider](../iformatprovider/) 객체가 제공하는 문화별 형식 정보를 사용하여 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&) | 지정된 값을 문자열로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&, const [String](../string/)\&) | 지정된 값을 지정된 문자열 형식을 사용하여 문자열로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), std::nullptr_t) | 지정된 유니코드 문자 배열을 문자열로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 유니코드 문자 배열을 지정된 [IFormatProvider](../iformatprovider/) 객체가 제공하는 문화별 형식 정보를 사용하여 문자열로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) | 지정된 값을 반환합니다; 변환이 수행되지 않습니다. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 값을 반환합니다; 변환이 수행되지 않습니다. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 지정된 값을 반환합니다; 변환이 수행되지 않습니다. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | 지정된 값을 반환합니다; 변환이 수행되지 않습니다. |
| static [String](../string/) [ToString](./tostring/)(char_t, std::nullptr_t) | 지정된 값을 반환합니다; 변환이 수행되지 않습니다. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 값을 반환합니다; 변환이 수행되지 않습니다. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 지정된 값을 반환합니다; 변환이 수행되지 않습니다. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 값을 반환합니다; 변환이 수행되지 않습니다. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 지정된 값을 반환합니다; 변환이 수행되지 않습니다. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, std::nullptr_t) | 지정된 값을 반환합니다; 변환이 수행되지 않습니다. |
| static [String](../string/) [ToString](./tostring/)(**bool**, std::nullptr_t) | 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, std::nullptr_t) | 지정된 값을 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, int) | 지정된 정수 값을 지정된 진법으로 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, int) | 지정된 정수 값을 지정된 진법으로 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, int) | 지정된 정수 값을 지정된 진법으로 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, int) | 지정된 정수 값을 지정된 진법으로 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 박싱된 값을 문자열 표현으로 변환합니다. 박싱된 값의 유형이 [String](../string/)인 경우, 변환 중에 지정된 문자열 형식이 사용됩니다. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**bool**) | 지정된 부울 값을 동등한 16비트 부호 없는 정수로 변환합니다. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint8_t**) | 지정된 8비트 부호 없는 정수를 동등한 16비트 부호 없는 정수로 변환합니다. |
| static **uint16_t** [ToUInt16](./touint16/)(**int8_t**) | 지정된 8비트 부호 있는 정수를 동등한 16비트 부호 없는 정수로 변환합니다. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint16_t**) | 지정된 16비트 부호 없는 정수를 반환합니다. |
| static **uint16_t** [ToUInt16](./touint16/)(**int16_t**) | 지정된 16비트 부호 있는 정수를 동등한 16비트 부호 없는 정수로 변환합니다. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint32_t**) | 지정된 32비트 부호 없는 정수를 동등한 16비트 부호 없는 정수로 변환합니다. |
| static **uint16_t** [ToUInt16](./touint16/)(**int32_t**) | 지정된 32비트 부호 있는 정수를 동등한 16비트 부호 없는 정수로 변환합니다. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint64_t**) | 지정된 64비트 부호 없는 정수를 동등한 16비트 부호 없는 정수로 변환합니다. |
| static **uint16_t** [ToUInt16](./touint16/)(**int64_t**) | 지정된 64비트 부호 있는 정수를 동등한 16비트 부호 없는 정수로 변환합니다. |
| static **uint16_t** [ToUInt16](./touint16/)(**float**) | 지정된 float 숫자를 동등한 16비트 부호 없는 정수로 변환합니다. |
| static **uint16_t** [ToUInt16](./touint16/)(**double**) | 지정된 double 숫자를 동등한 16비트 부호 없는 정수로 변환합니다. |
| static **uint16_t** [ToUInt16](./touint16/)(const [Decimal](../decimal/)\&) | 지정된 decimal 숫자를 동등한 16비트 부호 없는 정수로 변환합니다. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(char_t) | 지정된 유니코드 문자를 동등한 16비트 부호 없는 정수로 변환합니다. |
| static **uint16_t** [ToUInt16](./touint16/)([DateTime](../datetime/)) | 변환이 지원되지 않습니다. 항상 InvalidCastException을 발생시킵니다. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(std::nullptr_t) | 지정된 널 문자열을 동등한 부호 없는 16비트 정수 값으로 변환합니다. |
| static **uint16_t** [ToUInt16](./touint16/)(const char_t *) | 지정된 c-문자열(숫자의 문자열 표현 포함)을 동등한 부호 없는 16비트 정수 값으로 변환합니다. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&) | 지정된 문자열(숫자의 문자열 표현 포함)을 동등한 부호 없는 16비트 정수 값으로 변환합니다. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, int) | 지정된 진법으로 숫자의 문자열 표현을 포함하는 문자열을 동등한 부호 없는 16비트 정수 값으로 변환합니다. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 형식 정보를 사용하여 지정된 문자열 표현을 포함하는 문자열을 동등한 부호 없는 16비트 정수 값으로 변환합니다. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 형식 정보와 숫자 스타일을 사용하여 지정된 문자열 표현을 포함하는 문자열을 동등한 부호 없는 16비트 정수 값으로 변환합니다. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)([Enum](../enum/)) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 박싱된 값을 동등한 부호 없는 16비트 정수 값으로 변환합니다. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**bool**) | 지정된 부울 값을 동등한 32비트 부호 없는 정수로 변환합니다. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint8_t**) | 지정된 8비트 부호 없는 정수를 동등한 32비트 부호 없는 정수로 변환합니다. |
| static **uint32_t** [ToUInt32](./touint32/)(**int8_t**) | 지정된 8비트 부호 있는 정수를 동등한 32비트 부호 없는 정수로 변환합니다. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint16_t**) | 지정된 16비트 부호 없는 정수를 동등한 32비트 부호 없는 정수로 변환합니다. |
| static **uint32_t** [ToUInt32](./touint32/)(**int16_t**) | 지정된 16비트 부호 있는 정수를 동등한 32비트 부호 없는 정수로 변환합니다. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint32_t**) | 지정된 32비트 부호 없는 정수를 반환합니다. |
| static **uint32_t** [ToUInt32](./touint32/)(**int32_t**) | 지정된 32비트 부호 있는 정수를 동등한 32비트 부호 없는 정수로 변환합니다. |
| static **uint32_t** [ToUInt32](./touint32/)(**uint64_t**) | 지정된 64비트 부호 없는 정수를 동등한 32비트 부호 없는 정수로 변환합니다. |
| static **uint32_t** [ToUInt32](./touint32/)(**int64_t**) | 지정된 64비트 부호 있는 정수를 동등한 32비트 부호 없는 정수로 변환합니다. |
| static **uint32_t** [ToUInt32](./touint32/)(**float**) | 지정된 float 숫자를 동등한 32비트 부호 없는 정수로 변환합니다. |
| static **uint32_t** [ToUInt32](./touint32/)(**double**) | 지정된 double 숫자를 동등한 32비트 부호 없는 정수로 변환합니다. |
| static **uint32_t** [ToUInt32](./touint32/)(const [Decimal](../decimal/)\&) | 지정된 10진수 숫자를 동등한 32비트 부호 없는 정수로 변환합니다. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(char_t) | 지정된 유니코드 문자를 동등한 32비트 부호 없는 정수로 변환합니다. |
| static **uint32_t** [ToUInt32](./touint32/)([DateTime](../datetime/)) | 변환이 지원되지 않습니다. 항상 InvalidCastException이 발생합니다. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(std::nullptr_t) | 지정된 null 문자열을 동등한 부호 없는 32비트 정수 값으로 변환합니다. |
| static **uint32_t** [ToUInt32](./touint32/)(const char_t *) | 숫자의 문자열 표현을 포함하는 지정된 C 문자열을 동등한 부호 없는 32비트 정수 값으로 변환합니다. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&) | 숫자의 문자열 표현을 포함하는 지정된 문자열을 동등한 부호 없는 32비트 정수 값으로 변환합니다. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, int) | 지정된 진수에서 숫자의 문자열 표현을 포함하는 지정된 문자열을 동등한 부호 없는 32비트 정수 값으로 변환합니다. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 형식 정보를 사용하여 숫자의 문자열 표현을 포함하는 지정된 문자열을 동등한 부호 없는 32비트 정수 값으로 변환합니다. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 형식 정보와 숫자 스타일을 사용하여 숫자의 문자열 표현을 포함하는 지정된 문자열을 동등한 부호 없는 32비트 정수 값으로 변환합니다. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)([Enum](../enum/)) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 박싱된 값을 동등한 부호 없는 32비트 정수 값으로 변환합니다. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**bool**) | 지정된 부울 값을 동등한 64비트 부호 없는 정수로 변환합니다. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint8_t**) | 지정된 8비트 부호 없는 정수를 동등한 64비트 부호 없는 정수로 변환합니다. |
| static **uint64_t** [ToUInt64](./touint64/)(**int8_t**) | 지정된 8비트 부호 있는 정수를 동등한 64비트 부호 없는 정수로 변환합니다. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint16_t**) | 지정된 16비트 부호 없는 정수를 동등한 64비트 부호 없는 정수로 변환합니다. |
| static **uint64_t** [ToUInt64](./touint64/)(**int16_t**) | 지정된 16비트 부호 있는 정수를 동등한 64비트 부호 없는 정수로 변환합니다. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint32_t**) | 지정된 32비트 부호 없는 정수를 동등한 64비트 부호 없는 정수로 변환합니다. |
| static **uint64_t** [ToUInt64](./touint64/)(**int32_t**) | 지정된 32비트 부호 있는 정수를 동등한 64비트 부호 없는 정수로 변환합니다. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint64_t**) | 지정된 64비트 부호 없는 정수를 반환합니다. |
| static **uint64_t** [ToUInt64](./touint64/)(**int64_t**) | 지정된 64비트 부호 있는 정수를 동등한 64비트 부호 없는 정수로 변환합니다. |
| static **uint64_t** [ToUInt64](./touint64/)(**float**) | 지정된 float 숫자를 동등한 64비트 부호 없는 정수로 변환합니다. |
| static **uint64_t** [ToUInt64](./touint64/)(**double**) | 지정된 double 숫자를 동등한 64비트 부호 없는 정수로 변환합니다. |
| static **uint64_t** [ToUInt64](./touint64/)(const [Decimal](../decimal/)\&) | 지정된 10진수 숫자를 동등한 64비트 부호 없는 정수로 변환합니다. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(char_t) | 지정된 유니코드 문자를 동등한 64비트 부호 없는 정수로 변환합니다. |
| static **uint64_t** [ToUInt64](./touint64/)([DateTime](../datetime/)) | 변환이 지원되지 않습니다. 항상 InvalidCastException이 발생합니다. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(std::nullptr_t) | 지정된 null 문자열을 동등한 부호 없는 64비트 정수 값으로 변환합니다. |
| static **uint64_t** [ToUInt64](./touint64/)(const char_t *) | 숫자의 문자열 표현을 포함하는 지정된 C 문자열을 동등한 부호 없는 64비트 정수 값으로 변환합니다. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&) | 숫자의 문자열 표현을 포함하는 지정된 문자열을 동등한 부호 없는 64비트 정수 값으로 변환합니다. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, int) | 지정된 진수에서 숫자의 문자열 표현을 포함하는 지정된 문자열을 동등한 부호 없는 64비트 정수 값으로 변환합니다. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 형식 정보를 사용하여 숫자의 문자열 표현을 포함하는 지정된 문자열을 동등한 부호 없는 64비트 정수 값으로 변환합니다. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 제공된 형식 정보와 숫자 스타일을 사용하여 숫자의 문자열 표현을 포함하는 지정된 문자열을 동등한 부호 없는 64비트 정수 값으로 변환합니다. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)([Enum](../enum/)) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 박싱된 값을 동등한 부호 없는 64비트 정수 값으로 변환합니다. |
## 참조

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)