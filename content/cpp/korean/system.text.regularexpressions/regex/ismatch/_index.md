---
title: IsMatch()
second_title: Aspose.Slides for C++ API 참조
description: 정규식을 문자열과 매칭합니다.
type: docs
weight: 53
url: /ko/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) 메서드

정규식과 문자열을 매칭합니다.

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 대상 문자열. |
| startat | int | 시작 인덱스. |

### 반환값

문자열이 정규식과 매치되면 true, 그렇지 않으면 false.

## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) 메서드

문자열이 패턴과 매치되는지 확인합니다.

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 입력 문자열. |
| pattern | const [String](../../../system/string/)\& | 정규식 패턴. |
| options | [RegexOptions](../../regexoptions/) | 매칭 옵션. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | 시간 제한. |
| startat | int | [Match](../../match/) 시작 위치. |

### 반환값

매치를 찾으면 true, 그렇지 않으면 false.

## 참고

* 열거형 [RegexOptions](../../regexoptions/)
* 클래스 [String](../../../system/string/)
* 클래스 [Regex](../)
* 클래스 [TimeSpan](../../../system/timespan/)
* 네임스페이스 [System::Text::RegularExpressions](../../)
* 라이브러리 [Aspose.Slides](../../../)