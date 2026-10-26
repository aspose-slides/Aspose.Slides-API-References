---
title: Parse()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 문자열을 DateTimeOffset 등가 형태로 변환합니다.
type: docs
weight: 703
url: /ko/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) 메서드

지정된 문자열을 [DateTimeOffset](../) 등가 형태로 변환합니다.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 변환할 [String](../../string/). |

### 반환 값

[DateTimeOffset](../)는 **input**과 동일합니다.

## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) 메서드

지정된 문자열을 지정된 형식 공급자와 서식 스타일을 사용하여 [DateTimeOffset](../) 객체로 변환합니다.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 변환할 [String](../../string/). |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 형식 공급자. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 날짜 및 시간 서식 스타일. |

### 반환 값

[DateTimeOffset](../)는 **input**과 동일합니다.

## 참고

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)