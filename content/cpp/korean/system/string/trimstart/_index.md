---
title: TrimStart()
second_title: C++용 Aspose.Slides API 참조
description: 문자열 시작 부분의 모든 공백 문자를 제거합니다.
type: docs
weight: 690
url: /ko/system/string/trimstart/
---
## String::TrimStart() const 메서드

문자열 시작 부분에서 모든 공백 문자를 제거합니다.

```cpp
String System::String::TrimStart() const
```

### 반환 값

시작 부분에 공백이 없는 [String](../)

## String::TrimStart(char_t) const 메서드

문자열 시작 부분에서 전달된 문자의 모든 발생을 제거합니다.

```cpp
String System::String::TrimStart(char_t ch) const
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| ch | char_t | 제거할 기호. |

### 반환 값

제거 결과.

## String::TrimStart(const String\&) const 메서드

문자열 시작 부분에서 전달된 문자의 모든 발생을 제거합니다.

```cpp
String System::String::TrimStart(const String &anyOf) const
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) 제거할 문자. |

### 반환 값

제거된 문자가 없는 [String](../).

## String::TrimStart(const ArrayPtr\<char_t\>\&) const 메서드

문자열 시작 부분에서 전달된 문자의 모든 발생을 제거합니다.

```cpp
String System::String::TrimStart(const ArrayPtr<char_t> &anyOf) const
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 제거할 문자. |

### 반환 값

제거된 문자 없이 [String](../).

## 참조

* Typedef [ArrayPtr](../../arrayptr/)
* 클래스 [String](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)