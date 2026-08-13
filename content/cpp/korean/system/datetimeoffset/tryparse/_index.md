---
title: TryParse()
second_title: Aspose.Slides C++용 API 참조
description: 지정된 문자열을 DateTimeOffset 객체로 변환하려 시도합니다.
type: docs
weight: 729
url: /ko/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) 메서드

지정된 문자열을 [DateTimeOffset](../) 객체로 변환하려 시도합니다.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 변환할 [String](../../string/) |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../)는 **input**과 동등합니다. |

### 반환값

**input**이 성공적으로 변환되면 true, 그렇지 않으면 false.

## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) 메서드

지정된 문자열을 [DateTimeOffset](../) 객체로 변환하려 시도하며, 지정된 형식 공급자와 서식 스타일을 사용합니다.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 변환할 [String](../../string/) |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 포맷 제공자 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 날짜 및 시간 서식 스타일 |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../)는 **input**과 동등합니다. |

### 반환값

**input**이 성공적으로 변환되면 true, 그렇지 않으면 false.

## 참조

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTimeOffset](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)