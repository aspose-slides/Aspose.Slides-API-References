---
title: String()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 기본 생성자. null로 간주되는 문자열 객체를 생성합니다.
type: docs
weight: 14
url: /ko/system/string/string/
---
## String::String() 생성자

기본 생성자. 문자열 객체를 null로 간주합니다.

```cpp
System::String::String()
```

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) 생성자

문자열 리터럴을 기반으로 문자열을 생성합니다. 리터럴을 null-terminated 문자열로 간주하고, 리터럴 크기를 기준으로 목표 문자열 길이를 계산합니다.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | T\& | [String](../) 리터럴 포인터. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) 생성자

문자열 포인터를 기반으로 문자열을 생성합니다. 가리키는 문자열을 null-terminated 문자열로 취급하고, null 문자 기준으로 목표 문자열 길이를 계산합니다.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const T\& | 문자열 포인터. |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) 생성자

문자열 리터럴을 기반으로 문자열을 생성합니다. 리터럴을 UTF8의 null-terminated 문자열로 간주하고, 리터럴 크기를 기준으로 목표 문자열 길이를 계산합니다.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | T\& | [String](../) 리터럴 포인터. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) 생성자

문자열 포인터를 기반으로 문자열을 생성합니다. 가리키는 문자열을 UTF8의 null-terminated 문자열로 취급하고, null 문자 기준으로 목표 문자열 길이를 계산합니다.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const T\& | 문자열 포인터. |

## String::String(const char16_t *, int) 생성자

문자열 포인터와 명시적 길이를 사용해 문자열을 생성합니다.

```cpp
System::String::String(const char16_t *str, int length)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| str | const char16_t * | [String](../) 포인터, 리터럴 또는 배열일 수 있습니다. |
| length | int | 명시적 문자열 길이 |

## String::String(const ReadOnlySpan\<char16_t\>\&) 생성자

[System.String](../) 클래스의 새 인스턴스를 지정된 읽기 전용 span에 표시된 유니코드 문자로 초기화합니다.

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const [ReadOnlySpan](../../readonlyspan/)\<char16_t\>\& | 유니코드 문자들의 읽기 전용 span. |

## String::String(const char *, int) 생성자

문자열 포인터와 명시적 길이를 사용해 문자열을 생성합니다.

```cpp
System::String::String(const char *str, int length)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| str | const char * | [String](../) UTF8 데이터 포인터, 리터럴 또는 배열일 수 있습니다. |
| length | int | 명시적 문자열 길이 |

## String::String(const char16_t *, int, int) 생성자

시작 위치와 길이를 사용해 문자 포인터에서 문자열을 생성합니다.

```cpp
System::String::String(const char16_t *str, int start, int length)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| str | const char16_t * | [String](../) 포인터, 리터럴 또는 배열일 수 있습니다. |
| start | int | 시작 위치. |
| length | int | [String](../) 길이. |

## String::String(const char16_t, int) 생성자

채우기 생성자.

```cpp
System::String::String(const char16_t ch, int count)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| ch | const char16_t | 채우기 문자. |
| count | int | 목표 길이. |

## String::String(T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) 생성자

nullptr 생성자. 다른 템플릿 생성자와의 우선순위를 해결하기 위해 템플릿으로 선언됩니다.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | nullptr_t이어야 함 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const T\& | nullptr |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) 생성자

와이드 문자열 리터럴을 기반으로 문자열을 생성합니다. 리터럴을 null-terminated 문자열로 간주하고, 리터럴 크기를 기준으로 목표 문자열 길이를 계산합니다. 일부 플랫폼에서 **wchar_t** 변환은 시간이 많이 소요되므로 암시적 변환은 허용되지 않습니다.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | T\& | [String](../) 리터럴 포인터. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) 생성자

와이드 문자 문자열 포인터를 기반으로 문자열을 생성합니다. 가리키는 문자열을 null-terminated 문자열로 취급하고, null 문자를 기준으로 목표 문자열 길이를 계산합니다. 일부 플랫폼에서 **wchar_t** 변환은 시간이 많이 소요되므로 암시적 변환은 허용되지 않습니다.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | const T\& | 문자열 포인터. |

## String::String(const wchar_t *, int) 생성자

와이드 문자 문자열 포인터와 명시적 길이를 사용해 문자열을 생성합니다. 일부 플랫폼에서 **wchar_t** 변환은 시간이 많이 소요되므로 암시적 변환은 허용되지 않습니다.

```cpp
System::String::String(const wchar_t *str, int length)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| str | const **wchar_t** * | [String](../) 포인터, 리터럴 또는 배열일 수 있습니다. |
| length | int | 명시적 문자열 길이 |

## String::String(const wchar_t, int) 생성자

채우기 생성자. 일부 플랫폼에서 **wchar_t** 변환은 시간이 많이 소요되므로 암시적 변환은 허용되지 않습니다.

```cpp
System::String::String(const wchar_t ch, int count=1)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| ch | const **wchar_t** | 채우기 문자. |
| count | int | 목표 길이. |

## String::String(const String\&) 생성자

복사 생성자.

```cpp
System::String::String(const String &str)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 복사 대상. |

## String::String(String\&&) 생성자

이동 생성자.

```cpp
System::String::String(String &&str) noexcept
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| str | [String](../)\&& | [String](../) 로부터 데이터를 이동. |

## String::String(const ArrayPtr\<char16_t\>\&) 생성자

전체 문자 배열을 문자열로 변환합니다.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | [Array](../../array/) 문자열로 변환. |

## String::String(const ArrayPtr\<char16_t\>\&, int, int) 생성자

문자 배열의 부분 범위를 문자열로 변환합니다. 파라미터가 배열 범위를 벗어나면 빈 문자열이 생성됩니다.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | 문자 배열. |
| offset | int | 하위 배열 시작 인덱스. |
| len | int | 하위 배열 길이. |

## String::String(const codeporting_icu::UnicodeString\&) 생성자

UnicodeString을 [String](../) 로 래핑합니다.

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString을 [String](../) 로 래핑. |

## String::String(codeporting_icu::UnicodeString\&&) 생성자

이동 생성자.

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString을 [String](../) 로 래핑. |

## String::String(const std::wstring\&) 생성자

와이드 문자열에서 [String](../) 를 생성합니다.

```cpp
System::String::String(const std::wstring &str)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| str | const std::wstring\& | 와이드 문자열을 [String](../) 로 변환. |

## String::String(const std::u16string\&) 생성자

utf16 문자열에서 [String](../) 를 생성합니다.

```cpp
System::String::String(const std::u16string &str)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| str | const std::u16string\& | Utf16 문자열을 [String](../) 로 변환. |

## String::String(const std::string\&) 생성자

UTF-8 형식의 std::string 문자열에서 [String](../) 를 생성합니다.

```cpp
System::String::String(const std::string &utf8str)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| utf8str | const std::string\& | std::string 문자열을 [String](../) 로 변환. |

## String::String(const std::u32string\&) 생성자

std::u32string 문자열에서 [String](../) 를 생성합니다.

```cpp
System::String::String(const std::u32string &u32str)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| u32str | const std::u32string\& | std::u32string 문자열을 [String](../) 로 변환. |

## 참고

* Typedef [ArrayPtr](../../arrayptr/)
* 클래스 [String](../)
* 클래스 [ReadOnlySpan](../../readonlyspan/)
* 구조체 [IsStringLiteral](../../isstringliteral/)
* 구조체 [IsStringPointer](../../isstringpointer/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)