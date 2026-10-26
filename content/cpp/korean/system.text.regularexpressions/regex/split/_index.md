---
title: Split()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 정규식 일치 항목으로 문자열을 분할합니다.
type: docs
weight: 105
url: /ko/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) 메서드

정규식 일치 항목으로 문자열을 분할합니다.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/)을(를) 분할합니다. |

### 반환 값

[Array](../../../system/array/)은(는) 일치 항목 사이의 하위 문자열입니다.

## Regex::Split(const String\&, int) 메서드

정규식 일치 항목으로 문자열을 분할합니다.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/)을(를) 분할합니다. |
| count | int | 하위 문자열 제한 수. |

### 반환 값

[Array](../../../system/array/)은(는) 일치 항목 사이의 하위 문자열입니다.

## Regex::Split(const String\&, int, int) 메서드

입력 문자열을 지정된 최대 횟수만큼 하위 문자열 배열로 분할하며, [Regex](../) 생성자에서 지정된 정규식에 정의된 위치에서 수행합니다. 정규식 패턴 검색은 입력 문자열의 지정된 문자 위치에서 시작합니다.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 분할할 문자열. |
| count | int | 분할이 발생할 수 있는 최대 횟수. |
| startat | int | 검색이 시작될 입력 문자열의 문자 위치. |

### 반환 값

문자열 배열.

## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) 메서드

정규식으로 문자열을 분할합니다.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 입력 문자열. |
| pattern | const [String](../../../system/string/)\& | 정규식 패턴. |
| options | [RegexOptions](../../regexoptions/) | 매칭 옵션. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | 시간 제한. |

### 반환 값

[Array](../../../system/array/)은(는) 일치 항목 사이의 문자열입니다.

## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) 메서드

정규식으로 문자열을 분할합니다.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 입력 문자열. |
| pattern | const [String](../../../system/string/)\& | 정규식 패턴. |
| count | int | [Match](../../match/) 숫자 제한. |
| options | [RegexOptions](../../regexoptions/) | 매칭 옵션. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | 시간 제한. |

### 반환 값

[Array](../../../system/array/)은(는) 일치 항목 사이의 문자열입니다.

## 또 보기

* 열거형 [RegexOptions](../../regexoptions/)
* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [Regex](../)
* 클래스 [TimeSpan](../../../system/timespan/)
* 네임스페이스 [System::Text::RegularExpressions](../../)
* 라이브러리 [Aspose.Slides](../../../)