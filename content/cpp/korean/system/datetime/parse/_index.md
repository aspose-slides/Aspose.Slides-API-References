---
title: Parse()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 날짜 및 시간 값의 문자열 표현을 동등한 DateTime 객체로 변환합니다.
type: docs
weight: 859
url: /ko/system/datetime/parse/
---
## DateTime::Parse(const String\&) 메서드


지정된 날짜 및 시간 값의 문자열 표현을 동등한 [DateTime](../) 객체로 변환합니다.

```cpp
static DateTime System::DateTime::Parse(const String &s)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 변환할 날짜 및 시간 값의 문자열 표현. |

### 반환값

지정된 문자열이 나타내는 것과 동등한 날짜 및 시간 값을 나타내는 [DateTime](../) 클래스의 새 인스턴스입니다.

## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) 메서드


지정된 날짜 및 시간 값의 문자열 표현을 문화별 형식 정보를 사용하여 동등한 [DateTime](../) 객체로 변환합니다.

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 변환할 날짜 및 시간 값의 문자열 표현. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | [IFormatProvider](../../iformatprovider/) 객체는 문화별 형식 정보를 제공합니다. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | **s**에 대한 추가 정보, **s**에 존재할 수 있는 스타일 요소에 대한 정보, 또는 **s**를 [DateTime](../) 객체로 변환하는 방식에 대한 정보를 제공하는 열거형 값들의 비트 조합입니다. |

### 반환값

지정된 문자열이 나타내는 것과 동등한 날짜 및 시간 값을 나타내는 [DateTime](../) 클래스의 새 인스턴스입니다.

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) 메서드




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) 메서드




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) 메서드




```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## 참조

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)