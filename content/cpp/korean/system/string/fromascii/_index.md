---
title: FromAscii()
second_title: Aspose.Slides for C++ API 참조
description: ASCII 문자열에서 String을 생성합니다.
type: docs
weight: 950
url: /ko/system/string/fromascii/
---
## String::FromAscii(const char *) 메서드


ASCII 문자열에서 [String](../)를 생성합니다.

```cpp
static String System::String::FromAscii(const char *asciiStr)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| asciiStr | const char * | ASCII 코드 페이지를 사용해 인코딩된 널 종료 문자열에 대한 포인터입니다. |

### 반환 값

[String](../) 전달된 문자열을 나타내는 객체.

## String::FromAscii(const char *, int) 메서드


ASCII 문자열에서 [String](../)를 생성합니다.

```cpp
static String System::String::FromAscii(const char *asciiStr, int len)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| asciiStr | const char * | ASCII 코드 페이지를 사용해 인코딩된 문자열에 대한 포인터입니다. |
| len | int | 처리할 문자 수입니다. |

### 반환 값

[String](../) 전달된 문자열을 나타내는 객체.

## String::FromAscii(const std::string\&) 메서드


ASCII 문자열에서 [String](../)를 생성합니다.

```cpp
static String System::String::FromAscii(const std::string &asciiStr)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| asciiStr | const std::string\& | ASCII 인코딩 문자열입니다. |

### 반환 값

[String](../) 전달된 문자열을 나타내는 객체.

## 관련 항목

* 클래스 [String](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)