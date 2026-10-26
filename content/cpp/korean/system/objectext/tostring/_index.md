---
title: ToString()
second_title: Aspose.Slides for C++ API 참조
description: C# ToString 메서드의 대체 구현으로, 모든 C++ 타입에서 작동합니다.
type: docs
weight: 27
url: /ko/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) 메서드

C# ToString 메서드의 대체 구현으로, 모든 C++ 타입에서 작동합니다.

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) 문자열로 변환할 리터럴. |

### 반환 값

[String](../../string/) **obj**의 표현.

## ObjectExt::ToString(const Nullable\<T\>\&) 메서드

C# ToString 메서드의 대체 구현으로, 모든 C++ 타입에서 작동합니다.

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Nullable](../../nullable/) 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [Nullable](../../nullable/)\<T\>\& | [Nullable](../../nullable/) 문자열로 변환할 개체. |

### 반환 값

[String](../../string/) **obj**의 표현.

## ObjectExt::ToString(const T\&) 메서드

C# ToString 메서드의 대체 구현으로, 모든 C++ 타입에서 작동합니다.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Enum](../../enum/) 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) 문자열로 변환할 값. |

### 반환 값

[String](../../string/) **obj**의 표현.

## ObjectExt::ToString(const T\&) 메서드

C# ToString 메서드의 대체 구현으로, 모든 C++ 타입에서 작동합니다.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스마트 포인터 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) 문자열로 변환할 값. |

### 반환 값

[String](../../string/) **obj**의 표현.

## ObjectExt::ToString(T\&) 메서드

C# ToString 메서드의 대체 구현으로, 모든 C++ 타입에서 작동합니다.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스마트 포인터 타입 또는 [ExceptionWrapper](../../exceptionwrapper/). |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | T\& | 문자열로 변환할 스마트 포인터 또는 [ExceptionWrapper](../../exceptionwrapper/). |

### 반환 값

[String](../../string/) **obj**의 표현.

## ObjectExt::ToString(T\&) 메서드

C# ToString 메서드의 대체 구현으로, 모든 C++ 타입에서 작동합니다.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스칼라 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | T\& | 문자열로 변환할 스칼라 값. |

### 반환 값

[String](../../string/) **obj**의 표현.

## ObjectExt::ToString(T\&&) 메서드

C# ToString 메서드의 대체 구현으로, 모든 C++ 타입에서 작동합니다.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스칼라 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | T\&& | 문자열로 변환할 스칼라 값. |

### 반환 값

[String](../../string/) **obj**의 표현.

## ObjectExt::ToString(T\&) 메서드

C# ToString 메서드의 대체 구현으로, 모든 C++ 타입에서 작동합니다.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 구조체 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | T\& | 문자열로 변환할 구조체 값. |

### 반환 값

[String](../../string/) **obj**의 표현.

## ObjectExt::ToString(const T\&) 메서드

C# ToString 메서드의 대체 구현으로, 모든 C++ 타입에서 작동합니다.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 구조체 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const T\& | 문자열로 변환할 구조체 값. |

### 반환 값

[String](../../string/) **obj**의 표현.

## ObjectExt::ToString(T\&&) 메서드

C# ToString 메서드의 대체 구현으로, 모든 C++ 타입에서 작동합니다.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 스칼라 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | T\&& | 문자열로 변환할 스칼라 값. |

### 반환 값

[String](../../string/) **obj**의 표현.

## 참고

* 클래스 [String](../../string/)
* 클래스 [ObjectExt](../)
* 클래스 [Nullable](../../nullable/)
* 구조체 [IsSmartPtr](../../issmartptr/)
* 구조체 [IsExceptionWrapper](../../isexceptionwrapper/)
* 구조체 [IsNullable](../../isnullable/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)