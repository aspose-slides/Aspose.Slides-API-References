---
title: Replace()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 정규식과 일치하는 모든 항목을 문자열에서 교체 문자열로 바꿉니다.
type: docs
weight: 92
url: /ko/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const String\&) 메서드

문자열에서 정규식과 일치하는 모든 항목을 교체 문자열로 바꿉니다.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 입력 문자열. |
| replacement | const [String](../../../system/string/)\& | 교체 문자열. |

### 반환값

정규식과 일치하는 모든 항목이 교체 문자열로 바뀐 입력 문자열.

## Regex::Replace(const String\&, const char_t *) 메서드

문자열에서 정규식과 일치하는 모든 항목을 교체 문자열로 바꿉니다.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 입력 문자열. |
| replacement | const char_t * | 교체 문자열. |

### 반환값

정규식과 일치하는 모든 항목이 교체 문자열로 바뀐 입력 문자열.

## Regex::Replace(const String\&, const MatchEvaluator\&) 메서드

문자열의 모든 일치를 대리자가 생성한 교체 문자열로 바꿉니다.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 입력 문자열. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | 일치를 기반으로 교체 문자열을 생성하는 대리자. |

### 반환값

모든 일치가 교체된 입력 문자열.

## Regex::Replace(const String\&, const MatchEvaluator\&, int) 메서드

문자열의 모든 일치를 대리자가 생성한 교체 문자열로 바꿉니다.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 입력 문자열. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | 일치를 기반으로 교체 문자열을 생성하는 대리자. |
| count | int | 교체 횟수 제한. |

### 반환값

모든 일치가 교체된 입력 문자열.

## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) 메서드

문자열의 모든 일치를 대리자가 생성한 교체 문자열로 바꿉니다.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 입력 문자열. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | 일치를 기반으로 교체 문자열을 생성하는 대리자. |
| count | int | 교체 횟수 제한. |
| startat | int | 입력 문자열에서 교체를 시작할 [Index](../../../system/index/). |

### 반환값

모든 일치가 교체된 입력 문자열.

## Regex::Replace(const String\&, const String\&, int) 메서드

문자열에서 하위 문자열을 교체합니다. 아직 구현되지 않음.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Regex::Replace(const String\&, const String\&, int, int) 메서드

문자열에서 하위 문자열을 교체합니다. 아직 구현되지 않음.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Regex::Replace(const String\&, const char_t *, const char_t *) 메서드

문자열에서 정규식과 일치하는 모든 항목을 교체 문자열로 바꿉니다.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 입력 문자열. |
| pattern | const char_t * | [Regex](../) 패턴. |
| replacement | const char_t * | 교체 문자열. |

### 반환값

정규식과 일치하는 모든 항목이 교체 문자열로 바뀐 입력 문자열.

## Regex::Replace(const String\&, const String\&, const char_t *) 메서드

문자열에서 정규식과 일치하는 모든 항목을 교체 문자열로 바꿉니다.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 입력 문자열. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) 패턴. |
| replacement | const char_t * | 교체 문자열. |

### 반환값

정규식과 일치하는 모든 항목이 교체 문자열로 바뀐 입력 문자열.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) 메서드

문자열의 모든 일치를 대리자가 생성한 교체 문자열(정적 함수)로 바꿉니다.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 입력 문자열. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) 패턴. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | 일치를 기반으로 교체 문자열을 생성하는 대리자. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) 옵션. |

### 반환값

모든 일치가 교체된 입력 문자열.

## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) 메서드

문자열에서 정규식과 일치하는 모든 항목을 교체 문자열로 바꿉니다.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 입력 문자열. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) 패턴. |
| replacement | const [String](../../../system/string/)\& | 교체 문자열. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) 옵션. |

### 반환값

정규식과 일치하는 모든 항목이 교체 문자열로 바뀐 입력 문자열.

## Regex::Replace(const String\&, const String\&, const String\&) 메서드

정규식 일치를 교체합니다.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 입력 문자열. |
| pattern | const [String](../../../system/string/)\& | Regexp 패턴. |
| replacement | const [String](../../../system/string/)\& | 교체 문자열. |

### 반환값

[String](../../../system/string/)가 모든 일치가 교체된.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) 메서드

정규식 일치를 교체합니다.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | 입력 문자열. |
| pattern | const [String](../../../system/string/)\& | Regexp 패턴. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | 각 일치에 대해 교체 문자열을 생성하는 대리자. |

### 반환값

[String](../../../system/string/)가 모든 일치가 교체된.

## 참조

* 열거형 [RegexOptions](../../regexoptions/)
* 타입정의 [MatchEvaluator](../../matchevaluator/)
* 클래스 [String](../../../system/string/)
* 클래스 [Regex](../)
* 네임스페이스 [System::Text::RegularExpressions](../../)
* 라이브러리 [Aspose.Slides](../../../)