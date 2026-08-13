---
title: TryParseExact()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 형식, 문화별 형식 정보 및 스타일을 사용하여 지정된 날짜 및 시간 값의 문자열 표현을 동등한 DateTime 객체로 변환합니다. 문자열 표현의 형식은 지정된 형식과 정확히 일치해야 합니다.
type: docs
weight: 898
url: /ko/system/datetime/tryparseexact/
---
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) 메서드


지정된 날짜 및 시간 값의 문자열 표현을 지정된 형식, 문화별 형식 정보 및 스타일을 사용하여 동등한 [DateTime](../) 객체로 변환합니다. 문자열 표현의 형식은 지정된 형식과 정확히 일치해야 합니다.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 변환할 날짜 및 시간 값의 문자열 표현입니다. |
| format | const [String](../../string/)\& | 문자열 형식입니다. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문화별 형식 정보를 제공하는 [IFormatProvider](../../iformatprovider/) 객체입니다. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | **s**에 대해 추가 정보를 제공하거나, **s**에 존재할 수 있는 스타일 요소에 대해, 또는 **s**를 [DateTime](../) 객체로 변환할 때의 추가 정보를 제공하는 열거형 값들의 비트 연산 조합입니다. |
| result | [DateTime](../)\& | 변환이 성공하면 변환 결과를 포함하는 출력 인수입니다. |

### 반환값

변환이 성공하면 true, 그렇지 않으면 false.

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) 메서드




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) 메서드




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) 메서드




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) 메서드


지정된 날짜 및 시간 값의 문자열 표현을 지정된 형식들, 문화별 형식 정보 및 스타일을 사용하여 동등한 [DateTime](../) 객체로 변환합니다. 문자열 표현의 형식은 지정된 형식 중 하나와 정확히 일치해야 합니다.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 변환할 날짜 및 시간 값의 문자열 표현입니다. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | 문자열 형식들의 배열입니다. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문화별 형식 정보를 제공하는 [IFormatProvider](../../iformatprovider/) 객체입니다. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | **s**에 대해 추가 정보를 제공하거나, **s**에 존재할 수 있는 스타일 요소에 대해, 또는 **s**를 [DateTime](../) 객체로 변환할 때의 추가 정보를 제공하는 열거형 값들의 비트 연산 조합입니다. |
| result | [DateTime](../)\& | 변환이 성공하면 변환 결과를 포함하는 출력 인수입니다. |

### 반환값

변환이 성공하면 true, 그렇지 않으면 false.

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) 메서드




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) 메서드




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) 메서드




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## 관련 항목

* 열거형 [DateTimeStyles](../../../system.globalization/datetimestyles/)
* 타입정의 [SharedPtr](../../sharedptr/)
* 타입정의 [ArrayPtr](../../arrayptr/)
* 클래스 [String](../../string/)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [DateTime](../)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 클래스 [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)