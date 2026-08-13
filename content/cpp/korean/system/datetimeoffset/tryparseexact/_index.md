---
title: TryParseExact()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 형식, 형식 제공자 및 서식 스타일을 사용하여 지정된 문자열을 DateTimeOffset 객체로 변환하려고 시도합니다.
type: docs
weight: 742
url: /ko/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset&) 메서드


지정된 문자열을 지정된 형식, 형식 제공자 및 서식 스타일을 사용하여 [DateTimeOffset](../) 객체로 변환하려고 시도합니다.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/)을 변환합니다. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | 형식 문자열의 배열. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 형식 제공자. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 날짜 및 시간 서식 스타일. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../)는 **input**과 동등한 값입니다. |

### 반환값

**input**이(가) 성공적으로 변환되면 true, 그렇지 않으면 false.

## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset&) 메서드


지정된 문자열을 지정된 형식, 형식 제공자 및 서식 스타일을 사용하여 [DateTimeOffset](../) 객체로 변환하려고 시도합니다.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/)을 변환합니다. |
| format | const [String](../../string/)\& | 형식 문자열. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 형식 제공자. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 날짜 및 시간 서식 스타일. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../)는 **input**과 동등한 값입니다. |

### 반환값

**input**이(가) 성공적으로 변환되면 true, 그렇지 않으면 false.

## 참고

* 열거형 [DateTimeStyles](../../../system.globalization/datetimestyles/)
* 타입정의 [ArrayPtr](../../arrayptr/)
* 타입정의 [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 클래스 [DateTimeOffset](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)