---
title: Equals()
second_title: Aspose.Slides for C++ API 참조
description: C# Object.Equals 의미 체계를 사용하여 객체를 비교합니다.
type: docs
weight: 157
url: /ko/system/object/equals/
---
## Object::Equals(ptr) 메서드

C# [Object.Equals](./) 의미 체계를 사용하여 객체를 비교합니다.

```cpp
virtual bool System::Object::Equals(ptr obj)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | [ptr](../ptr/) | [Object](../) 현재 객체와 비교하기 위해. |

### 반환 값

객체가 서로 같다고 판단되면 true, 그렇지 않으면 false.

## Object::Equals(T1 const\&, T2 const\&) 메서드

C# 스타일로 참조 형식 객체를 비교합니다.

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 비교할 첫 번째 객체의 유형. |
| T2 | 비교할 두 번째 객체의 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| objA | T1 const\& | 비교할 첫 번째 객체. |
| objB | T2 const\& | 비교할 두 번째 객체. |

### 반환 값

객체가 레퍼런스로든 의미적으로든 ([Object.Equals](./)와 같은 비교) 일치하면 true, 그렇지 않으면 false.

## Object::Equals(T1 const\&, T2 const\&) 메서드

C# 스타일로 값 형식 객체를 비교합니다.

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 비교할 첫 번째 객체의 유형. |
| T2 | 비교할 두 번째 객체의 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| objA | T1 const\& | 비교할 첫 번째 객체. |
| objB | T2 const\& | 비교할 두 번째 객체. |

### 반환 값

사용 가능한 동등 연산자로 객체가 같은 것으로 판단되면 true, 그렇지 않으면 false.

## Object::Equals(float const\&, float const\&) 메서드

IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN이 서로 같다고 간주되는 C# 스타일 부동소수점 비교를 에뮬레이트합니다.

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| objA | **float** const\& | 좌측 부동소수점 값. |
| objB | **float** const\& | 우측 부동소수점 값. |

### 반환 값

**objA**와 **objB**가 모두 NaN이거나 같으면 true, 그렇지 않으면 false.

## Object::Equals(double const\&, double const\&) 메서드

IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN이 서로 같다고 간주되는 C# 스타일 부동소수점 비교를 에뮬레이트합니다.

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| objA | **double** const\& | 좌측 부동소수점 값. |
| objB | **double** const\& | 우측 부동소수점 값. |

### 반환 값

**objA**와 **objB**가 모두 NaN이거나 같으면 true, 그렇지 않으면 false.

## 관련 항목

* Typedef [ptr](../ptr/)
* 클래스 [Object](../)
* 구조체 [IsSmartPtr](../../issmartptr/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)