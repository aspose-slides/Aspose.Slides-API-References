---
title: Match()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 정규식을 문자열에 적용합니다.
type: docs
weight: 66
url: /ko/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) 메서드

정규식을 문자열에 적용합니다.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 대상 문자열. |

### 반환값

[Match](../../match/) 매치 상태와 하위 매치를 포함하는 값.

## Regex::Match(const String\&, int, int) 메서드

정규식을 문자열에 적용합니다.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 대상 문자열. |
| startat | int | 시작 인덱스. |
| length | int | 검색할 문자 수 (0이면 전체 문자열 검색). |

### 반환값

[Match](../../match/) 매치 상태와 하위 매치를 포함하는 값.

## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) 메서드

문자열과 패턴을 매치합니다.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 입력 문자열. |
| pattern | const [String](../../../system/string/)\& | 정규식 패턴. |
| options | [RegexOptions](../../regexoptions/) | 매칭 옵션. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | 제한 시간. |
| startat | int | [Match](../../match/) 시작 위치. |
| length | int | 검색할 문자 수 (0이면 제한이 없습니다). |

### 반환값

첫 번째 매치가 발견되었습니다.

## 관련 항목

* 열거형 [RegexOptions](../../regexoptions/)
* 타입정의 [MatchPtr](../../matchptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [Regex](../)
* 클래스 [TimeSpan](../../../system/timespan/)
* 네임스페이스 [System::Text::RegularExpressions](../../)
* 라이브러리 [Aspose.Slides](../../../)