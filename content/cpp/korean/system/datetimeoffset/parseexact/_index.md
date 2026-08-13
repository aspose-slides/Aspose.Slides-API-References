---
title: ParseExact()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 형식, 형식 제공자 및 서식 스타일을 사용하여 지정된 문자열을 DateTimeOffset 객체로 변환합니다.
type: docs
weight: 716
url: /ko/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) 메서드

지정된 문자열을 지정된 형식, 형식 제공자 및 서식 스타일을 사용하여 [DateTimeOffset](../) 객체로 변환합니다.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) 변환할. |
| format | const [String](../../string/)\& | 형식 문자열. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 형식 제공자. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 날짜 및 시간 서식 스타일. |

### 반환 값

[DateTimeOffset](../)는 **input**과 동일합니다.

## DateTimeOffset::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) 메서드

지정된 문자열을 지정된 형식들, 형식 제공자 및 서식 스타일을 사용하여 [DateTimeOffset](../) 객체로 변환합니다.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) 변환할. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | 형식 문자열의 [Array](../../array/). |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 형식 제공자. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 날짜 및 시간 서식 스타일. |

### 반환 값

[DateTimeOffset](../)는 **input**과 동일합니다.

## 참고

* 열거형 [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* 클래스 [DateTimeOffset](../)
* 클래스 [String](../../string/)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)