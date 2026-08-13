---
title: Format()
second_title: Aspose.Slides for C++ API 레퍼런스
description: C# 스타일로 문자열을 포맷합니다.
type: docs
weight: 885
url: /ko/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) method

C# 스타일로 문자열을 포맷합니다.

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Args | 문자열을 포맷할 인수. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 인수를 문자열로 변환하는 데 사용할 포맷 제공자. |
| format | const [String](../)\& | 포맷 문자열. |
| args | const Args\&... | 문자열을 포맷할 인수. |

## String::Format(std::nullptr_t, const String\&, const Args\&...) method

C# 스타일로 문자열을 포맷합니다.

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Args | 문자열을 포맷할 인수. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| format | std::nullptr_t | 포맷 문자열. |
| args | const [String](../)\& | 문자열을 포맷할 인수. |

## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) method

C# 스타일로 문자열을 포맷합니다.

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Args | 문자열을 포맷할 인수. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| format | std::nullptr_t | 포맷 문자열. |
| args | const char16_t(&) | 문자열을 포맷할 인수. |

## String::Format(const String\&, const Args\&...) method

C# 스타일로 문자열을 포맷합니다.

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Args | 문자열을 포맷할 인수. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| format | const [String](../)\& | 포맷 문자열. |
| args | const Args\&... | 문자열을 포맷할 인수. |

## String::Format(const String\&, const System::ArrayPtr\<T\>\&) method

C# 스타일로 문자열을 포맷합니다.

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 문자열을 포맷할 인수. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| format | const [String](../)\& | 포맷 문자열. |
| args | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | 문자열을 포맷할 인수. |

## 관련 항목

* 타입 정의 [SharedPtr](../../sharedptr/)
* 타입 정의 [ArrayPtr](../../arrayptr/)
* 클래스 [String](../)
* 클래스 [IFormatProvider](../../iformatprovider/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)