---
title: Decimal
second_title: Aspose.Slides for C++ API 참조
description: "10진수 값을 나타냅니다. 이 유형은 스택에 할당하고 값 또는 참조에 의해 함수에 전달해야 합니다. 이 유형의 객체를 관리하기 위해 System::SmartPtr 클래스를 사용하지 마십시오."
type: docs
weight: 261
url: /ko/system/decimal/
---
## Decimal 클래스

Represents a decimal number. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class Decimal
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static [Decimal](./) [Add](./add/)(const [Decimal](./)\&, const [Decimal](./)\&) | 두 개의 지정된 [Decimal](./) 값을 더합니다. |
| static [Decimal](./) [Ceiling](./ceiling/)(const [Decimal](./)\&) | 지정된 값보다 크거나 같은 가장 작은 정수 값을 반환합니다. |
| static int [Compare](./compare/)(const [Decimal](./)\&, const [Decimal](./)\&) | 첫 번째 [Decimal](./) 객체가 나타내는 값이 두 번째 [Decimal](./) 객체가 나타내는 값보다 작거나, 같은지, 큰지를 판단합니다. |
| int [CompareTo](./compareto/)(const [Decimal](./)\&) const | 현재 객체가 나타내는 값이 지정된 객체가 나타내는 값보다 작거나, 같은지, 큰지를 판단합니다. |
| [Decimal](./decimal/)() | 값이 0인 인스턴스를 생성합니다. |
| [Decimal](./decimal/)(std::int8_t) | 지정된 값을 나타내는 인스턴스를 생성합니다. |
| [Decimal](./decimal/)(std::int16_t) | 지정된 값을 나타내는 인스턴스를 생성합니다. |
| [Decimal](./decimal/)(std::int32_t) | 지정된 값을 나타내는 인스턴스를 생성합니다. |
| [Decimal](./decimal/)(std::int64_t) | 지정된 값을 나타내는 인스턴스를 생성합니다. |
| [Decimal](./decimal/)(std::uint8_t) | 지정된 값을 나타내는 인스턴스를 생성합니다. |
| [Decimal](./decimal/)(std::uint16_t) | 지정된 값을 나타내는 인스턴스를 생성합니다. |
| [Decimal](./decimal/)(std::uint32_t) | 지정된 값을 나타내는 인스턴스를 생성합니다. |
| [Decimal](./decimal/)(std::uint64_t) | 지정된 값을 나타내는 인스턴스를 생성합니다. |
| [Decimal](./decimal/)(**float**) | 지정된 값을 나타내는 인스턴스를 생성합니다. |
| [Decimal](./decimal/)(**double**) | 지정된 값을 나타내는 인스턴스를 생성합니다. |
| explicit [Decimal](./decimal/)(const std::string\&) | std::string 클래스의 인스턴스로 지정된 문자열 표현을 가진 값을 나타내는 인스턴스를 생성합니다. |
| [Decimal](./decimal/)(**int32_t**, **int32_t**, **int32_t**, **bool**, **uint8_t**) | 지정된 구성 요소들로 [Decimal](./) 객체를 생성합니다. |
| [Decimal](./decimal/)(const [Decimal](./)\&) | [Decimal](./) 객체와 동일한 수를 나타내는 [Decimal](./) 클래스의 인스턴스를 생성합니다. |
| [Decimal](./decimal/)(const [ArrayPtr](../arrayptr/)\<**int32_t**\>\&) | 바이너리 표현을 포함하는 정수 배열로부터 [Decimal](./) 클래스의 인스턴스를 생성합니다. |
| [Decimal](./decimal/)(std::nullptr_t) | 항상 ArgumentNullException을 발생시킵니다. |
| [Decimal](./decimal/)(const [number_type](./number_type/)\&) | 지정된 값을 나타내는 [Decimal](./) 클래스의 인스턴스를 생성합니다. |
| static [Decimal](./) [Divide](./divide/)(const [Decimal](./)\&, const [Decimal](./)\&) | 두 개의 지정된 [Decimal](./) 값을 나눕니다. |
| **bool** [Equals](./equals/)(const [Decimal](./)\&) const | 현재 객체와 지정된 객체가 나타내는 값이 같은지 판단합니다. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 현재 객체와 지정된 객체가 나타내는 값이 같은지 판단합니다. |
| static **bool** [Equals](./equals/)(const [Decimal](./)\&, const [Decimal](./)\&) | 지정된 객체들이 나타내는 값이 같은지 판단합니다. |
| static [Decimal](./) [Floor](./floor/)(const [Decimal](./)\&) | 지정된 값보다 작거나 같은 가장 큰 정수 값을 반환합니다. |
| static [Decimal](./) [FromOACurrency](./fromoacurrency/)(**int64_t**) | [Convert](../convert/) 지정된 OLE 통화 값을 동등한 [Decimal](./) 값으로 변환합니다. 구현되지 않음. |
| static [System::ArrayPtr](../arrayptr/)\<int\> [GetBits](./getbits/)(const [Decimal](./)\&) | 지정된 [Decimal](./) 객체를 해당 값의 바이너리 표현으로 변환합니다. |
| static void [GetBytes](./getbytes/)(const [Decimal](./)\&, const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Convert](../convert/) 지정된 [Decimal](./) 값을 바이트 배열로 변환합니다. |
| int [GetHashCode](./gethashcode/)() const | 현재 객체에 대한 해시 코드를 반환합니다. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | 객체 유형 코드를 가져옵니다. |
| static [Decimal](./) [Multiply](./multiply/)(const [Decimal](./)\&, const [Decimal](./)\&) | 두 개의 지정된 [Decimal](./) 값을 곱합니다. |
| static [Decimal](./) [Negate](./negate/)(const [Decimal](./)\&) | 지정된 객체가 나타내는 값을 부정한 결과 값을 나타내는 새로운 [Decimal](./) 클래스 인스턴스를 반환합니다. |
| explicit [operator bool](./operator_bool/)() const | 현재 객체가 나타내는 값을 불리언 값으로 변환합니다. |
| explicit [operator double](./operator_double/)() const | 현재 객체가 나타내는 값을 double 정밀 부동소수점 값으로 변환합니다. |
| explicit [operator float](./operator_float/)() const | 현재 객체가 나타내는 값을 single 정밀 부동소수점 값으로 변환합니다. |
| **bool** [operator!=](./operator_not_equal/)(const [Decimal](./)\&) const | 현재 객체와 지정된 객체가 나타내는 값이 같지 않은지 판단합니다. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 현재 객체가 나타내는 값이 0과 다른지 판단합니다. |
| [Decimal](./) [operator%](./operator%/)(const [Decimal](./)\&) const | 현재 객체와 지정된 객체가 나타내는 값으로 모듈로 연산을 수행한 결과 값을 나타내는 새로운 [Decimal](./) 클래스 인스턴스를 반환합니다. |
| [Decimal](./)\& [operator%=](./operator%_equal/)(const [Decimal](./)\&) | 현재 객체와 지정된 객체가 나타내는 값으로 모듈로 연산을 수행한 새로운 값을 현재 객체에 할당합니다. |
| [Decimal](./) [operator*](./operator_star/)(const [Decimal](./)\&) const | 현재 객체와 지정된 객체가 나타내는 값의 곱셈 결과 값을 나타내는 새로운 [Decimal](./) 클래스 인스턴스를 반환합니다. |
| [Decimal](./)\& [operator*=](./operator_star_equal/)(const [Decimal](./)\&) | 현재 객체와 지정된 객체가 나타내는 값의 곱셈 결과 값을 새로운 값으로 할당합니다. |
| [Decimal](./) [operator+](./operator_plus/)(const [Decimal](./)\&) const | 현재 객체와 지정된 객체가 나타내는 값의 합을 나타내는 새로운 [Decimal](./) 클래스 인스턴스를 반환합니다. |
| [Decimal](./)\& [operator++](./operator_plus_plus/)() | 현재 객체가 나타내는 값을 증가시킵니다. |
| [Decimal](./)\& [operator+=](./operator_plus_equal/)(const [Decimal](./)\&) | 현재 객체와 지정된 객체가 나타내는 값의 합을 새로운 값으로 할당합니다. |
| [Decimal](./) [operator-](./operator_minus/)(const [Decimal](./)\&) const | 현재 객체가 나타내는 값에서 지정된 객체가 나타내는 값을 빼서 얻은 결과 값을 나타내는 새로운 [Decimal](./) 클래스 인스턴스를 반환합니다. |
| [Decimal](./) [operator-](./operator_minus/)() const | 현재 객체가 나타내는 값을 부정한 결과 값을 나타내는 새로운 [Decimal](./) 클래스 인스턴스를 반환합니다. |
| [Decimal](./)\& [operator--](./operator_minus_minus/)() | 현재 객체가 나타내는 값을 감소시킵니다. |
| [Decimal](./)\& [operator-=](./operator_minus_equal/)(const [Decimal](./)\&) | 현재 객체가 나타내는 값에서 지정된 객체가 나타내는 값을 빼서 얻은 새 값을 현재 객체에 할당합니다. |
| [Decimal](./) [operator/](./operator_div/)(const [Decimal](./)\&) const | 현재 객체가 나타내는 값을 지정된 객체가 나타내는 값으로 나눈 결과 값을 나타내는 새로운 [Decimal](./) 클래스 인스턴스를 반환합니다. |
| [Decimal](./)\& [operator/=](./operator_div_equal/)(const [Decimal](./)\&) | 현재 객체가 나타내는 값을 지정된 객체가 나타내는 값으로 나눈 결과 값을 현재 객체에 할당합니다. |
| **bool** [operator<](./operator_less/)(const [Decimal](./)\&) const | 현재 객체가 나타내는 값이 지정된 객체가 나타내는 값보다 작은지 판단합니다. |
| **bool** [operator<=](./operator_less_equal/)(const [Decimal](./)\&) const | 현재 객체가 나타내는 값이 지정된 객체가 나타내는 값보다 작거나 같은지 판단합니다. |
| [Decimal](./)\& [operator=](./operator_equal/)(const [Decimal](./)\&) | 지정된 객체가 나타내는 값을 현재 객체에 할당합니다. |
| **bool** [operator==](./operator_equal_equal/)(const [Decimal](./)\&) const | 현재 객체와 지정된 객체가 나타내는 값이 같은지 판단합니다. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 현재 객체가 나타내는 값이 0인지 판단합니다. |
| **bool** [operator>](./operator_greater/)(const [Decimal](./)\&) const | 현재 객체가 나타내는 값이 지정된 객체가 나타내는 값보다 큰지 판단합니다. |
| **bool** [operator>=](./operator_greater_equal/)(const [Decimal](./)\&) const | 현재 객체가 나타내는 값이 지정된 객체가 나타내는 값보다 크거나 같은지 판단합니다. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&) | 10진수의 문자열 표현을 [Decimal](./) 클래스의 동등한 인스턴스로 변환합니다. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/)) | 지정된 스타일을 사용하여 10진수의 문자열 표현을 [Decimal](./) 클래스의 동등한 인스턴스로 변환합니다. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 형식 제공자를 사용하여 10진수의 문자열 표현을 [Decimal](./) 클래스의 동등한 인스턴스로 변환합니다. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 지정된 스타일과 형식 제공자를 사용하여 10진수의 문자열 표현을 [Decimal](./) 클래스의 동등한 인스턴스로 변환합니다. |
| static [Decimal](./) [Remainder](./remainder/)(const [Decimal](./)\&, const [Decimal](./)\&) | 두 [Decimal](./) 값을 나눈 후 나머지를 계산합니다. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, [MidpointRounding](../midpointrounding/)) | 지정된 값을 가장 가까운 정수로 반올림합니다. 매개변수는 지정된 값이 두 가장 가까운 수와 동일하게 가까운 경우 함수의 동작을 지정합니다. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, int, [MidpointRounding](../midpointrounding/)) | 지정된 값을 지정된 소수점 자리 수를 가진 가장 가까운 값으로 반올림합니다. 매개변수는 지정된 값이 두 가장 가까운 수와 동일하게 가까운 경우 함수의 동작을 지정합니다. |
| static [Decimal](./) [Subtract](./subtract/)(const [Decimal](./)\&, const [Decimal](./)\&) | 한 지정된 [Decimal](./) 값을 다른 지정된 값에서 빼줍니다. |
| static **uint8_t** [ToByte](./tobyte/)([Decimal](./)) | [Decimal](./) 값을 부호 없는 8비트 정수값으로 변환합니다. |
| static **double** [ToDouble](./todouble/)([Decimal](./)) | [Decimal](./) 값을 double 정밀 부동소수점 숫자로 변환합니다. |
| static **int16_t** [ToInt16](./toint16/)([Decimal](./)) | [Decimal](./) 값을 부호 있는 16비트 정수값으로 변환합니다. |
| static **int32_t** [ToInt32](./toint32/)([Decimal](./)) | [Decimal](./) 값을 부호 있는 32비트 정수값으로 변환합니다. |
| static **int64_t** [ToInt64](./toint64/)([Decimal](./)) | [Decimal](./) 값을 부호 있는 64비트 정수값으로 변환합니다. |
| static **int64_t** [ToOACurrency](./tooacurrency/)(const [Decimal](./)\&) | [Convert](../convert/) 지정된 [Decimal](./) 값을 동등한 OLE 통화 값으로 변환합니다. 구현되지 않음. |
| static **int8_t** [ToSByte](./tosbyte/)([Decimal](./)) | [Decimal](./) 값을 부호 있는 8비트 정수값으로 변환합니다. |
| static **float** [ToSingle](./tosingle/)([Decimal](./)) | [Decimal](./) 값을 single 정밀 부동소수점 숫자로 변환합니다. |
| std::string [ToStdString](./tostdstring/)() const | 객체가 나타내는 값의 문자열 표현을 포함하는 std::string 인스턴스를 반환합니다. |
| [String](../string/) [ToString](./tostring/)() const | 객체가 나타내는 값의 문자열 표현을 반환합니다. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 현재 객체를 문화별 형식 정보를 사용하여 문자열로 변환합니다. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [Decimal](./)\&, std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 지정된 [IFormatProvider](../iformatprovider/) 객체가 제공하는 문자열 형식 및 문화별 형식 정보를 사용하여 현재 객체를 문자열 표현으로 변환합니다. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [String](../string/) [ToStringInternal](./tostringinternal/)() const | 객체가 나타내는 값의 문자열 표현을 반환합니다. 내부 용도. |
| static **uint16_t** [ToUInt16](./touint16/)([Decimal](./)) | [Decimal](./) 값을 부호 없는 16비트 정수값으로 변환합니다. |
| static **uint32_t** [ToUInt32](./touint32/)([Decimal](./)) | [Decimal](./) 값을 부호 없는 32비트 정수값으로 변환합니다. |
| static **uint64_t** [ToUInt64](./touint64/)([Decimal](./)) | [Decimal](./) 값을 부호 없는 64비트 정수값으로 변환합니다. |
| static [Decimal](./) [Truncate](./truncate/)(const [Decimal](./)\&) | 지정된 [Decimal](./) 객체가 나타내는 값의 정수 부분과 동일하고 모든 소수점 이하가 버려진 값을 나타내는 [Decimal](./) 객체를 반환합니다. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Decimal](./)\&) | 숫자의 문자열 표현을 포함하는 지정된 문자열을 동등한 [Decimal](./) 값으로 변환합니다. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Decimal](./)\&) | 제공된 형식 정보와 숫자 스타일을 사용하여 숫자의 문자열 표현을 포함하는 지정된 문자열을 동등한 [Decimal](./) 값으로 변환합니다. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | [Decimal](./) 클래스의 형식 정보를 나타내는 [TypeInfo](../typeinfo/) 객체에 대한 참조를 반환합니다. |
| [~Decimal](./~decimal/)() | 소멸자. |

## 필드

| 필드 | 설명 |
| --- | --- |
| static [MaxValue](./maxvalue/) | [Decimal](./) 클래스가 표현할 수 있는 가장 큰 수를 나타냅니다. |
| static [MinusOne](./minusone/) | -1 값을 나타냅니다. |
| static [MinValue](./minvalue/) | [Decimal](./) 클래스가 표현할 수 있는 가장 작은 수를 나타냅니다. |
| static [One](./one/) | 1 값을 나타냅니다. |
| static [Zero](./zero/) | 0 값을 나타냅니다. |

## 타입 정의

| 타입 정의 | 설명 |
| --- | --- |
| [number_type](./number_type/) | Detail::decimal_number_type의 별칭입니다. |

## 비고

```cpp
#include "system/console.h"
#include "system/decimal.h"

int main()
{
  using namespace System;

  Console::WriteLine(Decimal::MinValue);
  Console::WriteLine(Decimal::MaxValue);

  auto dividend = Decimal::One;
  auto divisor = 6;
  Console::WriteLine(dividend/divisor);

  return 0;
}
/*
이 코드 예제는 다음과 같은 출력을 생성합니다:
- 79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## 참조

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)