---
title: Matches()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 주어진 문자열에서 정규식을 반복 매칭하여 모든 일치를 가져옵니다.
type: docs
weight: 79
url: /ko/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) 메서드

Gets all matches of regex in given string by matching repeatedly.

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 입력 문자열. |
| startat | int | [Index](../../../system/index/)에서 매칭을 시작합니다. |

### 반환 값

Collection of all matches found.

## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) 메서드

Gets all matches between string and pattern.

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 입력 문자열. |
| pattern | const [String](../../../system/string/)\& | 정규식 패턴. |
| options | [RegexOptions](../../regexoptions/) | 매칭 옵션. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | 시간 제한. |
| startat | int | [Match](../../match/) 시작 위치. |
| length | int | 검색할 문자 수 (0이면 제한이 비활성화됩니다). |

### 반환 값

All matches found by matching repeatedly.

## 참조

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [Regex](../)
* 클래스 [TimeSpan](../../../system/timespan/)
* 네임스페이스 [System::Text::RegularExpressions](../../)
* 라이브러리 [Aspose.Slides](../../../)