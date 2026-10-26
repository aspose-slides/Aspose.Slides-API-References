---
title: Trim()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문자열의 시작과 끝에서 모든 공백 문자를 제거합니다.
type: docs
weight: 677
url: /ko/system/string/trim/
---
## String::Trim() const 메서드


문자열의 시작과 끝에서 모든 공백 문자를 제거합니다.

```cpp
String System::String::Trim() const
```


### 반환값

[String](../) 앞뒤에 공백이 없는.

## String::Trim(char_t) const 메서드


전달된 문자를 문자열의 시작과 끝에서 모두 제거합니다.

```cpp
String System::String::Trim(char_t ch) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ch | char_t | 제거할 기호. |

### 반환값

제거 결과.

## String::Trim(const String\&) const 메서드


전달된 문자들을 문자열의 시작과 끝에서 모두 제거합니다.

```cpp
String System::String::Trim(const String &anyOf) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| anyOf | const [String](../)\& | 삭제할 문자 [String](../). |

### 반환값

[String](../) 제거된 문자를 제외한.

## String::Trim(const ArrayPtr\<char_t\>\&) const 메서드


전달된 문자들을 문자열의 시작과 끝에서 모두 제거합니다.

```cpp
String System::String::Trim(const ArrayPtr<char_t> &anyOf) const
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 삭제할 문자 [Array](../../array/). |

### 반환값

[String](../) 제거된 문자를 제외한.

## 참조

* Typedef [ArrayPtr](../../arrayptr/)
* 클래스 [String](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)