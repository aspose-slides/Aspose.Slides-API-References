---
title: TrimEnd()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문자열 끝에서 모든 공백 문자를 제거합니다.
type: docs
weight: 703
url: /ko/system/string/trimend/
---
## String::TrimEnd() const 메서드

문자열 끝에서 모든 공백 문자를 제거합니다.

```cpp
String System::String::TrimEnd() const
```

### 반환 값

[String](../)는 앞에 공백이 없는 문자열을 반환합니다.

## String::TrimEnd(char_t) const 메서드

문자열 끝에서 전달된 문자 모든 발생을 제거합니다.

```cpp
String System::String::TrimEnd(char_t ch) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ch | char_t | 제거할 기호. |

### 반환 값

제거 결과.

## String::TrimEnd(const String&) const 메서드

문자열 끝에서 전달된 문자들의 모든 발생을 제거합니다.

```cpp
String System::String::TrimEnd(const String &anyOf) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| anyOf | const [String](../)& | [String](../) 제거할 문자. |

### 반환 값

[String](../)는 제거된 문자가 없는 문자열을 반환합니다.

## String::TrimEnd(const ArrayPtr<char_t>&) const 메서드

문자열 끝에서 전달된 문자들의 모든 발생을 제거합니다.

```cpp
String System::String::TrimEnd(const ArrayPtr<char_t> &anyOf) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)<char_t>& | [Array](../../array/) 제거할 문자. |

### 반환 값

[String](../)는 제거된 문자가 없는 문자열을 반환합니다.

## 참조

* Typedef [ArrayPtr](../../arrayptr/)
* 클래스 [String](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)