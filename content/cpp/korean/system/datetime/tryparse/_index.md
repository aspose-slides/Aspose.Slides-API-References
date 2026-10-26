---
title: TryParse()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 날짜 및 시간 값의 문자열 표현을 동등한 DateTime 객체로 변환합니다.
type: docs
weight: 885
url: /ko/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, DateTime\&) 메서드

지정된 날짜 및 시간 값의 문자열 표현을 동등한 [DateTime](../) 개체로 변환합니다.

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | 변환할 날짜 및 시간 값의 문자열 표현입니다. |
| result | [DateTime](../)\& | 변환이 성공하면 변환 결과를 포함하는 출력 인수입니다. |

### 반환값

변환이 성공하면 true, 그렇지 않으면 false.

## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) 메서드

지정된 문자열 표현을 문화별 형식 정보와 스타일을 사용하여 동등한 [DateTime](../) 개체로 변환합니다.

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | 변환할 날짜 및 시간 값의 문자열 표현입니다. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | [IFormatProvider](../../iformatprovider/) 개체는 문화별 형식 정보를 제공합니다. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 비트 연산으로 결합된 열거형 값으로, **s**에 대한 추가 정보, **s**에 존재할 수 있는 스타일 요소, 또는 **s**를 [DateTime](../) 개체로 변환하는 과정에 대한 추가 정보를 제공합니다. |
| result | [DateTime](../)\& | 변환이 성공하면 변환 결과를 포함하는 출력 인수입니다. |

### 반환값

변환이 성공하면 true, 그렇지 않으면 false.

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) 메서드

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) 메서드

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) 메서드

```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## 참조

* 열거형 [DateTimeStyles](../../../system.globalization/datetimestyles/)
* 타입정의 [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 클래스 [DateTime](../)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 클래스 [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)