---
title: Equals()
second_title: Aspose.Slides for C++ API 참조
description: 
type: docs
weight: 14
url: /ko/system/objectext/equals/
---
## ObjectExt::Equals(const T\&, const T2\&) 메서드




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## ObjectExt::Equals(const T\&, const T2\&) 메서드

C# [Object.Equals](../../object/equals/) 호출을 대체하며 C++에서 모든 타입에 대해 작동합니다. 스마트 포인터 타입에 대한 오버로드.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 첫 번째 객체 유형. |
| T2 | 두 번째 객체 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const T\& | 첫 번째 객체. |
| another | const T2\& | 두 번째 객체. |

### 반환값

객체가 동일하다고 판단되면 true, 그렇지 않으면 false.

## ObjectExt::Equals(T, const T2\&) 메서드

C# [Object.Equals](../../object/equals/) 호출을 대체하며 C++에서 모든 타입에 대해 작동합니다. 구조체 타입에 대한 오버로드.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 첫 번째 객체 유형. |
| T2 | 두 번째 객체 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | T | 첫 번째 객체. |
| another | const T2\& | 두 번째 객체. |

### 반환값

객체가 동일하다고 판단되면 true, 그렇지 않으면 false.

## ObjectExt::Equals(const T\&, const T2\&) 메서드

C# [Object.Equals](../../object/equals/) 호출을 대체하며 C++에서 모든 타입에 대해 작동합니다. 스칼라 타입에 대한 오버로드.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 첫 번째 객체 유형. |
| T2 | 두 번째 객체 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const T\& | 첫 번째 객체. |
| another | const T2\& | 두 번째 객체. |

### 반환값

객체가 동일하다고 판단되면 true, 그렇지 않으면 false.

## ObjectExt::Equals(const char_t(&), String) 메서드

C# [Object.Equals](../../object/equals/) 호출을 대체하며 C++에서 모든 타입에 대해 작동합니다. 문자열 리터럴과 문자열 비교에 대한 오버로드.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| N | [String](../../string/) 리터럴 크기. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) 리터럴. |
| another | [String](../../string/) | [String](../../string/). |

### 반환값

문자열이 일치하면 true, 그렇지 않으면 false.

## ObjectExt::Equals(const float\&, const float\&) 메서드

IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 모방하여 두 NaN이 동일하게 간주됩니다.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const **float**\& | LHS 부동소수점 값. |
| another | const **float**\& | RHS 부동소수점 값. |

### 반환값

**obj**와 **another**가 모두 NaN이거나 동일하면 true, 그렇지 않으면 false.

## ObjectExt::Equals(const double\&, const double\&) 메서드

IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동소수점 비교를 모방하여 두 NaN이 동일하게 간주됩니다.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const **double**\& | LHS 부동소수점 값. |
| another | const **double**\& | RHS 부동소수점 값. |

### 반환값

**obj**와 **another**가 모두 NaN이거나 동일하면 true, 그렇지 않으면 false.

## 참고

* 클래스 [ObjectExt](../)
* 클래스 [String](../../string/)
* 구조체 [IsExceptionWrapper](../../isexceptionwrapper/)
* 구조체 [IsSmartPtr](../../issmartptr/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)