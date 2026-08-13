---
title: Concat()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문자열 배열을 연결합니다.
type: docs
weight: 1
url: /ko/system.stringextra/concat/
---
## System::StringExtra::Concat(const ArrayPtr\<String\>\&) 함수

문자열 배열을 연결합니다.

```cpp
String System::StringExtra::Concat(const ArrayPtr<String> &parts)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| parts | const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\& | [Array](../../system/array/) 문자열을 연결하기 위한 |

### 반환 값

결합된 문자열.

## System::StringExtra::Concat(const String\&, const String\&) 함수

문자열을 연결합니다.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | 첫 번째 연결할 문자열. |
| str1 | const [String](../../system/string/)\& | 두 번째 연결할 문자열. |

### 반환 값

결합된 매개변수 문자열.

## System::StringExtra::Concat(const String\&, const String\&, const String\&) 함수

문자열을 연결합니다.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | 첫 번째 연결할 문자열. |
| str1 | const [String](../../system/string/)\& | 두 번째 연결할 문자열. |
| str2 | const [String](../../system/string/)\& | 세 번째 연결할 문자열. |

### 반환 값

결합된 매개변수 문자열.

## System::StringExtra::Concat(const String\&, const String\&, const String\&, const String\&) 함수

문자열을 연결합니다.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2, const String &str3)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | 첫 번째 연결할 문자열. |
| str1 | const [String](../../system/string/)\& | 두 번째 연결할 문자열. |
| str2 | const [String](../../system/string/)\& | 세 번째 연결할 문자열. |
| str3 | const [String](../../system/string/)\& | 네 번째 연결할 문자열. |

### 반환 값

결합된 매개변수 문자열.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) 함수

여러 개의 객체를 문자열로 변환하고 결과 문자열을 연결합니다. [SmartPtr](../../system/smartptr/) 형식에 대한 특수화.

```cpp
template<typename T> std::enable_if_t<IsSmartPtr<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) 변환 및 연결할 |

### 반환 값

[String](../../system/string/) 값이 모든 객체의 문자열 표현에서 결합됩니다.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) 함수

여러 개의 객체를 문자열로 변환하고 결과 문자열을 연결합니다. 산술형에 대한 특수화.

```cpp
template<typename T> std::enable_if_t<std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) 변환 및 연결할 |

### 반환 값

[String](../../system/string/) 값이 모든 객체의 문자열 표현에서 결합됩니다.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) 함수

여러 개의 객체를 문자열로 변환하고 결과 문자열을 연결합니다. 구조체 및 기타 값 형식에 대한 특수화.

```cpp
template<typename T> std::enable_if_t<!IsSmartPtr<T>::value &&!std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) 변환 및 연결할 |

### 반환 값

[String](../../system/string/) 값이 모든 객체의 문자열 표현에서 결합됩니다.

## 참고

* 타입정의 [ArrayPtr](../../system/arrayptr/)
* 클래스 [String](../../system/string/)
* 구조체 [IsSmartPtr](../../system/issmartptr/)
* 네임스페이스 [System::StringExtra](../)
* 라이브러리 [Aspose.Slides](../../)