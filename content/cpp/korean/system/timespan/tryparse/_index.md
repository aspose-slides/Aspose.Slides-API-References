---
title: TryParse()
second_title: Aspose.Slides for C++ API 참조
description: 문자열을 동등한 TimeSpan 객체로 변환하고 변환 결과를 반환합니다.
type: docs
weight: 560
url: /ko/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String\&, TimeSpan\&) 메서드

문자열을 동등한 [TimeSpan](../) 객체로 변환하고 변환 결과를 반환합니다.

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 입력 문자열. |
| result | [TimeSpan](../)\& | 문자열에 해당하는 시간 간격. |

### 반환 값

문자열이 성공적으로 변환된 경우 true; 그렇지 않으면 false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) 메서드

문자열을 지정된 형식 제공자를 사용하여 동등한 [TimeSpan](../) 객체로 변환하고 변환 결과를 반환합니다.

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 입력 문자열. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 문화별 형식 정보를 제공하는 형식 제공자. |
| result | [TimeSpan](../)\& | 문자열에 해당하는 시간 간격. |

### 반환 값

문자열이 성공적으로 변환된 경우 true; 그렇지 않으면 false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) 메서드




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) 메서드




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, std::nullptr_t, TimeSpan\&) 메서드




```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## 참조

* 타입정의 [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 클래스 [TimeSpan](../)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [CultureInfo](../../../system.globalization/cultureinfo/)
* 클래스 [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)