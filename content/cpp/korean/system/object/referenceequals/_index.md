---
title: ReferenceEquals()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "문자열 및 nullptr 경우에 대한 Object::ReferenceEquals의 특수화."
type: docs
weight: 261
url: /ko/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) 메서드

문자열 및 nullptr 경우에 대한 [Object::ReferenceEquals](./)의 특수화.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | [String](../../string/) const\& | [String](../../string/) nullptr와 비교하기 위해 |

### 반환 값

문자열이 null이면 true, 그렇지 않으면 false.

## Object::ReferenceEquals(String const\&, String const\&) 메서드

문자열 경우에 대한 [Object::ReferenceEquals](./)의 특수화.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str1 | [String](../../string/) const\& | 비교할 첫 번째 문자열. |
| str2 | [String](../../string/) const\& | 비교할 두 번째 문자열. |

### 반환 값

문자열이 일치하면 true, 그렇지 않으면 false.

## Object::ReferenceEquals(ptr const\&, ptr const\&) 메서드

객체를 참조로 비교합니다.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| objA | [ptr](../ptr/) const\& | 비교할 첫 번째 포인터. |
| objB | [ptr](../ptr/) const\& | 비교할 두 번째 포인터. |

### 반환 값

포인터가 일치하면 True, 그렇지 않으면 false.

## Object::ReferenceEquals(T const\&, T const\&) 메서드

객체를 참조로 비교합니다.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 비교할 객체의 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| objA | T const\& | 비교할 첫 번째 객체. |
| objB | T const\& | 비교할 두 번째 객체. |

### 반환 값

객체 주소가 일치하면 True, 그렇지 않으면 false.

## Object::ReferenceEquals(T const\&, std::nullptr_t) 메서드

값 형식 객체를 nullptr와 참조 비교합니다.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 비교할 객체의 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| objA | T const\& | 비교할 첫 번째 객체. |

### 반환 값

값 형식은 null이 될 수 없으므로 항상 false를 반환합니다.

## 참고

* 타입정의 [ptr](../ptr/)
* 클래스 [String](../../string/)
* 클래스 [Object](../)
* 구조체 [IsSmartPtr](../../issmartptr/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)