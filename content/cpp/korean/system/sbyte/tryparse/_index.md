---
title: TryParse()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 지정된 문자열(숫자의 문자열 표현 포함)을 8비트 부호 있는 정수로 변환합니다.
type: docs
weight: 14
url: /ko/system/sbyte/tryparse/
---
## SByte::TryParse(const String\&, int8_t\&) 메서드


지정된 문자열(숫자의 문자열 표현 포함)을 8비트 부호 있는 정수로 변환합니다.

```cpp
static bool System::SByte::TryParse(const String &value, int8_t &result)
```


### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열입니다. |
| result | **int8_t**\& | 변환 결과가 저장될 8비트 부호 있는 정수 변수에 대한 참조입니다. |

### Return Value

변환에 성공하면 true, 그렇지 않으면 false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int8_t\&) 메서드


제공된 서식 정보와 숫자 스타일을 사용하여 지정된 문자열(숫자의 문자열 표현 포함)을 8비트 부호 있는 정수로 변환합니다.

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int8_t &result)
```


### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 변환할 문자열입니다. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 숫자 문자열 표현에 허용되는 스타일을 지정하는 NumberStyles 열거형 값들의 비트 결합입니다. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문자열 서식 정보를 포함하는 객체에 대한 포인터입니다. |
| result | **int8_t**\& | 변환 결과가 저장될 8비트 부호 있는 정수 변수에 대한 참조입니다. |

### Return Value

변환에 성공하면 true, 그렇지 않으면 false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int8_t\&) 메서드




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int8_t\&) 메서드




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int8_t\&) 메서드




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int8_t &result)
```

## See Also

* 열거형 [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 클래스 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 구조체 [SByte](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)