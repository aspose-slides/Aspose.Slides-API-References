---
title: String
second_title: C++용 Aspose.Slides API 레퍼런스
description: "String 클래스는 라이브러리 전반에서 사용됩니다. 코드를 변환할 때 C# System.String을 대신합니다. 최적화 이유로 Object 서브클래스로 간주되지 않습니다. 이 타입은 스택에 할당하고 값이나 레퍼런스로 함수에 전달해야 합니다. 이 타입의 객체를 관리하기 위해 System::SmartPtr 클래스를 절대 사용하지 마세요."
type: docs
weight: 1275
url: /ko/system/string/
---
## String 클래스

[String](./) 클래스는 라이브러리 전반에서 사용됩니다. 코드 변환 시 C# [System.String](./)의 대체품입니다. 최적화 이유로 [Object](../object/)의 서브클래스로 간주되지 않습니다. 이 유형은 스택에 할당하고 값이나 레퍼런스로 함수에 전달해야 합니다. [System::SmartPtr](../smartptr/) 클래스를 사용해 이 유형의 객체를 관리하지 마세요.

```cpp
class String
```
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  [ASPOSECPP_VALUE_TYPE_IMPLEMENTS_INTERFACES](./asposecpp_value_type_implements_interfaces/)() | [String](./)는 C++ 측의 값 타입이며, 암시적으로(상속 없이) 일부 인터페이스를 구현합니다. |
| const UChar * [begin](./begin/)() const | 실제 문자열 버퍼의 시작을 가리키는 포인터를 반환합니다. 절대 재할당하지 않습니다. 버퍼가 null-terminated임을 보장하지 않습니다. |
| [String](./) [Clone](./clone/)() const | 현재 문자열의 복사본을 생성합니다. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**) | 두 서브스트링을 less-equal-greater 비교합니다. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 두 서브스트링을 less-equal-greater 비교합니다. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | 두 문자열을 less-equal-greater 비교합니다. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) | 두 문자열을 less-equal-greater 비교합니다. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**) | 두 문자열을 less-equal-greater 비교합니다. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 두 문자열을 less-equal-greater 비교합니다. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, const [String](./)\&) | 두 문자열을 ordinal 모드로 less-equal-greater 비교합니다. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, int, const [String](./)\&, int, int) | 두 문자열을 ordinal 모드로 less-equal-greater 비교합니다. |
| int [CompareTo](./compareto/)(const [String](./)\&) const | 두 문자열을 'less-equals-more' 스타일로 비교합니다. 현재 문화권을 사용합니다. |
| static [String](./) [Concat](./concat/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&) | 문자열을 연결합니다. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&) | 문자열을 연결합니다. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&) | 문자열을 연결합니다. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&, const [String](./)\&) | 문자열을 연결합니다. |
| **bool** [Contains](./contains/)(const [String](./)\&) const | str이 현재 문자열의 서브스트링인지 확인합니다. |
| **bool** [Contains](./contains/)(char16_t) const | 문자열이 주어진 문자를 포함하는지 확인합니다. |
| static [String](./) [Copy](./copy/)(const [String](./)\&) | 문자열 복사본을 생성합니다. |
| void [CopyTo](./copyto/)(int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) const | 문자열 문자들을 기존 배열 요소에 복사합니다. 크기 조정은 수행되지 않습니다. |
| const UChar * [end](./end/)() const | 실제 문자열 버퍼의 끝을 가리키는 포인터를 반환합니다. 절대 재할당하지 않습니다. 버퍼가 null-terminated임을 보장하지 않습니다. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&) const | 문자열이 지정된 서브스트링으로 끝나는지 확인합니다. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | 문자열이 지정된 서브스트링으로 끝나는지 확인합니다. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | 문자열이 지정된 서브스트링으로 끝나는지 확인합니다. |
| **bool** [Equals](./equals/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | [String](./) 동등성 비교. StringComparison 열거형에서 제공하는 여러 모드가 지원됩니다. |
| **bool** [Equals](./equals/)(const [String](./)\&) const | [String](./) 동등성 비교. [System::StringComparison::Ordinal](../stringcomparison/) 비교 모드를 사용합니다. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&) | Ordinal 비교 모드로 두 문자열을 동등 비교합니다. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | 두 문자열을 동등 비교합니다. |
| int [FastToAscii](./fasttoascii/)(char, int) const | [String](./)를 ASCII 문자열로 변환하려 시도합니다. |
| static [String](./) [Format](./format/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, const [String](./)\&, const Args\&...) | C# 스타일로 문자열을 포맷합니다. |
| static [String](./) [Format](./format/)(std::nullptr_t, const [String](./)\&, const Args\&...) | C# 스타일로 문자열을 포맷합니다. |
| static [String](./) [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | C# 스타일로 문자열을 포맷합니다. |
| static [String](./) [Format](./format/)(const [String](./)\&, const Args\&...) | C# 스타일로 문자열을 포맷합니다. |
| static [String](./) [Format](./format/)(const [String](./)\&, const [System::ArrayPtr](../arrayptr/)\<T\>\&) | C# 스타일로 문자열을 포맷합니다. |
| static [String](./) [FromAscii](./fromascii/)(const char *) | ASCII 문자열에서 [String](./)를 생성합니다. |
| static [String](./) [FromAscii](./fromascii/)(const char *, int) | ASCII 문자열에서 [String](./)를 생성합니다. |
| static [String](./) [FromAscii](./fromascii/)(const std::string\&) | ASCII 문자열에서 [String](./)를 생성합니다. |
| static [String](./) [FromUtf16](./fromutf16/)(const std::u16string\&) | utf16 문자열에서 [String](./)를 생성합니다. |
| static [String](./) [FromUtf32](./fromutf32/)(const **uint32_t** *, **int32_t**) | utf32 문자열에서 [String](./)를 생성합니다. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *) | utf8 문자열에서 [String](./)를 생성합니다. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *, int) | utf8 문자열에서 [String](./)를 생성합니다. |
| static [String](./) [FromUtf8](./fromutf8/)(const **uint8_t** *) | utf8 문자열에서 [String](./)를 생성합니다. |
| static [String](./) [FromUtf8](./fromutf8/)(const std::string\&) | utf8 문자열에서 [String](./)를 생성합니다. |
| static [String](./) [FromWCS](./fromwcs/)(const std::wstring\&) | 와이드 문자열에서 [String](./)를 생성합니다. |
| int [get_Length](./get_length/)() const | 문자열 길이를 가져옵니다. |
| int [GetHashCode](./gethashcode/)() const | 포함된 문자열을 해시합니다. ICU에서 구현되었으며, C#의 해시와 일치하지 않습니다. |
| int [IndexOf](./indexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | 서브스트링 앞쪽 조회. |
| int [IndexOf](./indexof/)(char_t, int) const | 문자 앞쪽 조회. |
| int [IndexOf](./indexof/)(char_t, int, int) const | 서브스트링 내 문자 앞쪽 조회. |
| int [IndexOf](./indexof/)(const [String](./)\&, int) const | 서브스트링 앞쪽 조회. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | 서브스트링 앞쪽 조회. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) const | 서브스트링 앞쪽 조회. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int) const | 서브스트링 앞쪽 조회. |
| int [IndexOfAny](./indexofany/)(char_t, int) const | 문자 앞쪽 조회. |
| int [IndexOfAny](./indexofany/)(const [String](./)\&, int) const | 결과적으로 이 문자열에서 str의 모든 문자를 찾습니다. 첫 번째 문자를 찾으면 그 위치를 반환하고, 그렇지 않으면 두 번째 문자를 찾는 식으로 진행합니다. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | 전체 문자열에서 전달된 문자 중 하나를 찾습니다. 첫 번째 문자열 문자를 anyOf의 모든 문자와 비교하고, 두 번째 문자와 계속 비교합니다. 대상 문자 중 일치하는 첫 번째 문자의 인덱스를 반환합니다. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | 서브스트링에서 전달된 문자 중 하나를 찾습니다. 첫 번째 문자열 문자를 anyOf의 모든 문자와 비교하고, 두 번째 문자와 계속 비교합니다. 대상 문자 중 일치하는 첫 번째 문자의 인덱스를 반환합니다. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | 서브스트링에서 전달된 문자 중 하나를 찾습니다. 첫 번째 문자열 문자를 anyOf의 모든 문자와 비교하고, 두 번째 문자와 계속 비교합니다. 대상 문자 중 일치하는 첫 번째 문자의 인덱스를 반환합니다. |
| [String](./) [Insert](./insert/)(int, const [String](./)\&) const | 지정된 위치에 서브스트링을 삽입합니다. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | 문자열 객체가 전달된 [TypeInfo](../typeinfo/)에 지정된 유형인지 확인합니다. |
| **bool** [IsAsciiString](./isasciistring/)() const | [String](./)가 ASCII 기호만 포함하는지 표시합니다. |
| **bool** [IsEmpty](./isempty/)() const | 문자열이 null이 아니면서 비어 있는지 확인합니다. |
| **bool** [IsNormalized](./isnormalized/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | 유니코드 문자열이 지정된 정규화 형태로 정규화되었는지 확인합니다. |
| **bool** [IsNull](./isnull/)() const | 문자열이 null로 간주되는지 확인합니다. [String](./)는 [String()](./string/) 생성자를 통해 생성되었거나, null 문자열에서 이동, 복사, 할당되었거나 [reset()](./reset/) 메서드가 호출된 경우에만 null입니다. |
| **bool** [IsNullOrEmpty](./isnullorempty/)() const | 문자열이 비어 있거나 null로 간주되는지 확인합니다. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [String](./)\&) | 전달된 문자열이 null이거나 비어 있는지 확인합니다. |
| static **bool** [IsNullOrWhiteSpace](./isnullorwhitespace/)(const [String](./)\&) | 지정된 문자열이 null인지, 비어 있는지, 또는 공백 문자만으로 구성되어 있는지 표시합니다. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, int) | 문자열을 구분자로 사용하여 배열을 결합합니다. |
| static [String](./) [Join](./join/)(const [String](./)\&, const System::Details::ArrayView\<[String](./)\>\&, int, int) | 문자열을 구분자로 사용하여 배열을 결합합니다. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](./)\>\>\&) | 문자열을 구분자로 사용하여 배열을 결합합니다. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\&) | 문자열을 구분자로 사용하여 배열을 결합합니다. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int) const | 서브스트링 뒤쪽 조회. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | 서브스트링 뒤쪽 조회. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | 서브스트링 뒤쪽 조회. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, int, [StringComparison](../stringcomparison/)) const | 서브스트링 뒤쪽 조회. |
| int [LastIndexOf](./lastindexof/)(char_t) const | 문자 뒤쪽 조회. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**) const | 문자 뒤쪽 조회. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**, **int32_t**) const | 문자 뒤쪽 조회. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | 전체 문자열을 뒤에서부터 전달된 문자 중 하나를 찾습니다. 마지막 문자열 문자를 anyOf의 모든 문자와 비교하고, 앞의 문자와 계속 비교합니다. 첫 번째 일치 항목의 인덱스를 반환합니다. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | 서브스트링에서 전달된 문자 중 하나를 찾습니다. 마지막 문자열 문자를 anyOf의 모든 문자와 비교하고, 앞의 문자와 계속 비교합니다. 첫 번째 일치 항목의 인덱스를 반환합니다. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | 서브스트링에서 전달된 문자 중 하나를 찾습니다. 마지막 문자열 문자를 anyOf의 모든 문자와 비교하고, 앞의 문자와 계속 비교합니다. 첫 번째 일치 항목의 인덱스를 반환합니다. |
| [String](./) [Normalize](./normalize/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | 지정된 정규화 형태를 사용하여 유니코드 문자열을 정규화합니다. |
|  [operator ReadOnlySpan< char16_t >](./operator_readonlyspan_less_char16_t__greater/)() const | 문자열을 읽기 전용 span으로 변환합니다. |
| **bool** [operator!=](./operator_not_equal/)(const [String](./)\&) const | 비동등 비교 연산자. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 문자열이 null이 아닌지 확인합니다. [IsNull()](./isnull/) 호출과 동일한 논리를 적용합니다. |
| [String](./) [operator+](./operator_plus/)(const [String](./)\&) const | [String](./) 연결 연산자. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | [String](./) 문자열 리터럴 또는 문자 문자열 포인터와 연결. |
| [String](./) [operator+](./operator_plus/)(char_t) const | 문자열 끝에 문자를 추가합니다. |
| [String](./) [operator+](./operator_plus/)(int) const | 정수값 문자열 표현을 문자열 끝에 추가합니다. |
| [String](./) [operator+](./operator_plus/)(**uint32_t**) const | 부호 없는 정수값 문자열 표현을 문자열 끝에 추가합니다. |
| [String](./) [operator+](./operator_plus/)(**double**) const | 부동소수점 값 문자열 표현을 문자열 끝에 추가합니다. |
| [String](./) [operator+](./operator_plus/)(**int64_t**) const | 정수값 문자열 표현을 문자열 끝에 추가합니다. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | 레퍼런스 타입 객체의 문자열 표현을 문자열 끝에 추가합니다. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | 레퍼런스 타입 객체의 문자열 표현을 문자열 끝에 추가합니다. |
| [String](./) [operator+](./operator_plus/)(T) const | 불리언 값 문자열 표현을 문자열 끝에 추가합니다. |
| [String](./)\& [operator+=](./operator_plus_equal/)(char_t) | 연결 할당 연산자. |
| [String](./)\& [operator+=](./operator_plus_equal/)(const [String](./)\&) | 연결 할당 연산자. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**double**) | 연결 할당 연산자. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint8_t**) | 연결 할당 연산자. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int16_t**) | 연결 할당 연산자. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint16_t**) | 연결 할당 연산자. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int32_t**) | 연결 할당 연산자. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint32_t**) | 연결 할당 연산자. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int64_t**) | 연결 할당 연산자. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint64_t**) | 연결 할당 연산자. |
| [String](./)\& [operator+=](./operator_plus_equal/)(T) | 연결 할당 연산자. |
| **bool** [operator<](./operator_less/)(const [String](./)\&) const | 문자열을 순서 비교합니다. |
| [String](./)\& [operator=](./operator_equal/)(const [String](./)\&) | 할당 연산자. |
| [String](./)\& [operator=](./operator_equal/)([String](./)\&&) | 이동 할당 연산자. |
| **bool** [operator==](./operator_equal_equal/)(const [String](./)\&) const | 등가 비교 연산자. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 문자열이 null인지 확인합니다. [IsNull()](./isnull/) 호출과 동일한 로직을 적용합니다. |
| **bool** [operator>](./operator_greater/)(const [String](./)\&) const | 문자열을 순서 비교합니다. |
| char_t [operator[]](./operator[]/)(int) const | 지정된 위치의 문자를 가져옵니다. |
| [String](./) [PadLeft](./padleft/)(int, char_t) const | 원래 문자열의 왼쪽에 패딩을 추가합니다. |
| [String](./) [PadRight](./padright/)(int, char_t) const | 원래 문자열의 오른쪽에 패딩을 추가합니다. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() const | 실제 문자열 버퍼의 마지막 문자(있는 경우)로의 역방향 반복자를 반환합니다. |
| [String](./) [Remove](./remove/)(**int32_t**, **int32_t**) const | 현재 문자열에서 하위 문자열을 제외한 모든 것을 추출합니다. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() const | 실제 문자열 버퍼의 첫 문자 이전(있는 경우)으로의 역방향 반복자를 반환합니다. |
| [String](./) [Replace](./replace/)(char_t, char_t) const | 문자열에서 문자 모든 발생을 교체합니다. |
| [String](./) [Replace](./replace/)(const [String](./)\&, const [String](./)\&) const | 이 문자열에서 lookup의 모든 발생을 교체합니다. |
| [String](./)\& [reset](./reset/)() | 문자열을 null로 설정합니다. C#에서 'string_variable_name = null'와 유사합니다. |
| [String](./)\& [SetCharAt](./setcharat/)(int, char_t) | 지정된 위치에 문자를 설정합니다. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, [StringSplitOptions](../stringsplitoptions/)) const | 문자를 기준으로 문자열을 분할합니다. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | 문자를 기준으로 문자열을 분할합니다. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, char_t, [StringSplitOptions](../stringsplitoptions/)) const | 두 문자 중 하나를 기준으로 문자열을 분할합니다. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, [StringSplitOptions](../stringsplitoptions/)) const | 지정된 문자 중 하나를 기준으로 문자열을 분할합니다. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | 지정된 문자 중 하나를 기준으로 문자열을 분할합니다. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, [StringSplitOptions](../stringsplitoptions/)) const | 하위 문자열을 기준으로 문자열을 분할합니다. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, int, [StringSplitOptions](../stringsplitoptions/)) const | 하위 문자열을 기준으로 문자열을 분할합니다. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, [StringSplitOptions](../stringsplitoptions/)) const | 하위 문자열을 기준으로 문자열을 분할합니다. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, [StringSplitOptions](../stringsplitoptions/)) const | 하위 문자열을 기준으로 문자열을 분할합니다. 현재는 구분자 배열이 0개 또는 1개인 경우만 지원합니다. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&) const | 문자열이 지정된 하위 문자열로 시작하는지 확인합니다. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | 문자열이 지정된 하위 문자열로 시작하는지 확인합니다. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | 문자열이 지정된 하위 문자열로 시작하는지 확인합니다. |
|  [String](./string/)() | 기본 생성자. null로 간주되는 문자열 객체를 생성합니다. |
|  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char16_t\>::value\>::type *) | 문자열 리터럴을 기반으로 문자열을 구성합니다. 리터럴을 null-terminated 문자열로 간주하고 리터럴 크기를 기준으로 목표 문자열 길이를 계산합니다. |
|  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char16_t\>::value\>::type *) | 문자 문자열 포인터를 기반으로 문자열을 구성합니다. 가리키는 문자열을 null-terminated로 간주하고 null 문자 기준으로 목표 문자열 길이를 계산합니다. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char\>::value\>::type *) | UTF8 문자열 리터럴을 기반으로 문자열을 구성합니다. 리터럴을 null-terminated 문자열로 간주하고 리터럴 크기를 기준으로 목표 문자열 길이를 계산합니다. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char\>::value\>::type *) | UTF8 문자 문자열 포인터를 기반으로 문자열을 구성합니다. 가리키는 문자열을 UTF8 null-terminated로 간주하고 null 문자 기준으로 목표 문자열 길이를 계산합니다. |
|  [String](./string/)(const char16_t *, int) | 문자 문자열 포인터와 명시적 길이로부터 문자열을 구성합니다. |
|  [String](./string/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) | 지정된 읽기 전용 스팬에 표시된 유니코드 문자로 [System.String](./) 클래스의 새 인스턴스를 초기화합니다. |
|  [String](./string/)(const char *, int) | 문자 문자열 포인터와 명시적 길이로부터 문자열을 구성합니다. |
|  [String](./string/)(const char16_t *, int, int) | 시작 위치와 길이를 사용하여 문자 문자열 포인터에서 문자열을 구성합니다. |
| explicit  [String](./string/)(const char16_t, int) | 채우기 생성자. |
|  [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | nullptr 생성자. 다른 템플릿 생성자와의 우선순위를 해결하기 위해 템플릿으로 선언되었습니다. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, **wchar_t**\>::value\>::type *) | 와이드 문자열 리터럴을 기반으로 문자열을 구성합니다. 리터럴을 null-terminated 문자열로 간주하고 리터럴 크기를 기준으로 목표 문자열 길이를 계산합니다. 일부 플랫폼에서는 **wchar_t** 변환이 시간이 오래 걸리므로 암시적 변환이 허용되지 않습니다. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, **wchar_t**\>::value\>::type *) | 와이드 문자 문자열 포인터를 기반으로 문자열을 구성합니다. 가리키는 문자열을 null-terminated로 간주하고 null 문자 기준으로 목표 문자열 길이를 계산합니다. 일부 플랫폼에서는 **wchar_t** 변환이 시간이 오래 걸리므로 암시적 변환이 허용되지 않습니다. |
| explicit  [String](./string/)(const **wchar_t** *, int) | 와이드 문자 문자열 포인터와 명시적 길이로부터 문자열을 구성합니다. 일부 플랫폼에서는 **wchar_t** 변환이 시간이 오래 걸리므로 암시적 변환이 허용되지 않습니다. |
| explicit  [String](./string/)(const **wchar_t**, int) | 채우기 생성자. 일부 플랫폼에서는 **wchar_t** 변환이 시간이 오래 걸리므로 암시적 변환이 허용되지 않습니다. |
|  [String](./string/)(const [String](./)\&) | 복사 생성자. |
|  [String](./string/)([String](./)\&&) | 이동 생성자. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&) | 전체 문자 배열을 문자열로 변환합니다. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, int) | 문자 배열 부분 범위를 문자열로 변환합니다. 매개변수가 배열 범위를 벗어나면 빈 문자열이 생성됩니다. |
| explicit  [String](./string/)(const codeporting_icu::UnicodeString\&) | UnicodeString을 [String](./)에 래핑합니다. |
| explicit  [String](./string/)(codeporting_icu::UnicodeString\&&) | 이동 생성자. |
| explicit  [String](./string/)(const std::wstring\&) | [String](./)을 와이드 문자열에서 생성합니다. |
| explicit  [String](./string/)(const std::u16string\&) | [String](./)을 utf16 문자열에서 생성합니다. |
| explicit  [String](./string/)(const std::string\&) | UTF-8 형식으로 제공된 std::string 문자열에서 [String](./)를 생성합니다. |
| explicit  [String](./string/)(const std::u32string\&) | std::u32string 문자열에서 [String](./)를 생성합니다. |
| [String](./) [Substring](./substring/)(**int32_t**) const | 하위 문자열을 추출합니다. |
| [String](./) [Substring](./substring/)(**int32_t**, **int32_t**) const | 하위 문자열을 추출합니다. |
| std::string [ToAsciiString](./toasciistring/)() const | 문자열을 std::string으로 변환합니다. ASCII 인코딩을 사용합니다. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)(**int32_t**, **int32_t**, **bool**) const | 문자열 또는 하위 문자열을 바이트 배열로 변환합니다. |
| [ArrayPtr](../arrayptr/)\<char_t\> [ToCharArray](./tochararray/)(**int32_t**, **int32_t**) const | 문자열 또는 하위 문자열을 문자 배열로 변환합니다. |
| [String](./) [ToLower](./tolower/)() const | 문자열의 모든 문자를 소문자로 변환합니다. |
| [String](./) [ToLower](./tolower/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | 특정 문화권을 사용하여 문자열의 모든 문자를 소문자로 변환합니다. |
| [String](./) [ToLowerInvariant](./tolowerinvariant/)() const | 불변 문화권을 사용하여 문자열의 모든 문자를 소문자로 변환합니다. |
| [String](./) [ToString](./tostring/)() const | [ToString()](./tostring/)가 값 유형 객체에서 호출되는 상황에서 [String](./) 클래스를 처리하기 위한 래퍼입니다. |
| [String](./) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | [ToString()](./tostring/)가 값 유형 객체에서 호출되는 상황에서 [String](./) 클래스를 처리하기 위한 래퍼입니다. |
| std::u16string [ToU16Str](./tou16str/)() const | 문자열을 std::u16string으로 변환합니다. |
| std::u32string [ToU32Str](./tou32str/)() const | 문자열을 std::u32string으로 변환합니다. |
| [String](./) [ToUpper](./toupper/)() const | 문자열의 모든 문자를 대문자로 변환합니다. |
| [String](./) [ToUpper](./toupper/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | 특정 문화권을 사용하여 문자열의 모든 문자를 대문자로 변환합니다. |
| [String](./) [ToUpperInvariant](./toupperinvariant/)() const | 불변 문화권을 사용하여 문자열의 모든 문자를 대문자로 변환합니다. |
| std::string [ToUtf8String](./toutf8string/)() const | 문자열을 std::string으로 변환합니다. UTF-8 인코딩을 사용합니다. |
| std::wstring [ToWCS](./towcs/)() const | 문자열을 std::wstring으로 변환합니다. |
| [String](./) [Trim](./trim/)() const | 문자열의 앞과 뒤에서 모든 공백 문자를 제거합니다. |
| [String](./) [Trim](./trim/)(char_t) const | 문자열의 앞과 뒤에서 전달된 문자의 모든 발생을 제거합니다. |
| [String](./) [Trim](./trim/)(const [String](./)\&) const | 문자열의 앞과 뒤에서 전달된 문자들의 모든 발생을 제거합니다. |
| [String](./) [Trim](./trim/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | 문자열의 앞과 뒤에서 전달된 문자들의 모든 발생을 제거합니다. |
| [String](./) [TrimEnd](./trimend/)() const | 문자열 끝에서 모든 공백 문자를 제거합니다. |
| [String](./) [TrimEnd](./trimend/)(char_t) const | 문자열 끝에서 전달된 문자의 모든 발생을 제거합니다. |
| [String](./) [TrimEnd](./trimend/)(const [String](./)\&) const | 문자열 끝에서 전달된 문자들의 모든 발생을 제거합니다. |
| [String](./) [TrimEnd](./trimend/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | 문자열 끝에서 전달된 문자들의 모든 발생을 제거합니다. |
| [String](./) [TrimStart](./trimstart/)() const | 문자열 시작에서 모든 공백 문자를 제거합니다. |
| [String](./) [TrimStart](./trimstart/)(char_t) const | 문자열 시작에서 전달된 문자의 모든 발생을 제거합니다. |
| [String](./) [TrimStart](./trimstart/)(const [String](./)\&) const | 문자열 시작에서 전달된 문자들의 모든 발생을 제거합니다. |
| [String](./) [TrimStart](./trimstart/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | 문자열 시작에서 전달된 문자들의 모든 발생을 제거합니다. |
| const UChar * [u_str](./u_str/)() const | ICU 스타일의 null-terminated 버퍼를 반환합니다. 문자열을 재할당할 수 있습니다. |
|  [~String](./~string/)() | 소멸자. |

## 필드

| 필드 | 설명 |
| --- | --- |
| static [Empty](./empty/) | 빈 문자열. |
| static [Null](./null/) | Null 문자열. |

## 타입 정의

| 타입 정의 | 설명 |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | 역방향 반복자 유형. |

## 비고



```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // 문자 배열에서 문자열을 구성하고 출력합니다.
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // 바이트 배열에서 문자열을 구성하고 출력합니다.
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // 아래 문자열을 트림하고 출력합니다.
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // 문자열의 단어 수를 출력합니다.
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
이 코드 예제는 다음과 같은 출력을 생성합니다:
hello
world
"This string contains whitespaces in the beginning and at the end."
단어 수: 11
*/
```

## 참조

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)