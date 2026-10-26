---
title: GetDateTimeFormats()
second_title: Aspose.Slides for C++ API 참조
description: 표준 날짜 및 시간 형식 지정자 중 하나로 포맷된 현재 객체의 문자열 표현을 각 요소로 하는 문자열 배열을 반환합니다.
type: docs
weight: 547
url: /ko/system/datetime/getdatetimeformats/
---
## DateTime::GetDateTimeFormats() const 메서드

현재 객체를 표준 날짜 및 시간 형식 지정자 중 하나로 형식화한 문자열을 각 요소로 하는 문자열 배열을 반환합니다.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats() const
```

## DateTime::GetDateTimeFormats(char_t) const 메서드

지정된 표준 날짜 및 시간 형식 지정자를 사용하여 현재 객체를 형식화한 문자열을 각 요소로 하는 문자열 배열을 반환합니다.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| format | char_t | 표준 날짜 및 시간 형식 지정자. |

## DateTime::GetDateTimeFormats(const SharedPtr\<IFormatProvider\>\&) const 메서드

표준 날짜 및 시간 형식 지정자 중 하나와 지정된 형식 제공자를 사용하여 현재 객체를 형식화한 문자열을 각 요소로 하는 문자열 배열을 반환합니다.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(const SharedPtr<IFormatProvider> &provider) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 형식 제공자. |

## DateTime::GetDateTimeFormats(char_t, const SharedPtr\<IFormatProvider\>\&) const 메서드

지정된 표준 날짜 및 시간 형식 지정자와 형식 제공자를 사용하여 현재 객체를 형식화한 문자열을 각 요소로 하는 문자열 배열을 반환합니다.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format, const SharedPtr<IFormatProvider> &provider) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| format | char_t | 표준 날짜 및 시간 형식 지정자. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 형식 제공자. |

## 참조

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 클래스 [DateTime](../)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)