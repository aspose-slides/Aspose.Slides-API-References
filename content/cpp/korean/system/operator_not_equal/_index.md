---
title: operator!=()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 
type: docs
weight: 2055
url: /ko/system/operator_not_equal/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) 함수




```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator!=(std::nullptr_t, DateTime) 함수




```cpp
constexpr bool System::operator!=(std::nullptr_t, DateTime)
```

## System::operator!=(std::nullptr_t, const DateTimeOffset\&) 함수




```cpp
constexpr bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) 함수


지정된 [Nullable](../nullable/) 개체가 null이 아닌 값을 나타내는지 확인합니다.

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| other | std::nullptr_t | 테스트할 [Nullable](../nullable/) 개체에 대한 상수 참조 |

### 반환값

지정된 개체가 null이 아닌 값을 나타내면 true, 그렇지 않으면 false

## System::operator!=(const T1\&, const Nullable\<T2\>\&) 함수


지정된 값이 [Nullable](../nullable/) 개체가 나타내는 값에 [operator!=()](./)를 적용했을 때 동일하지 않은지 확인합니다.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 첫 번째 비교값의 유형 |
| T2 | 두 번째 비교값을 나타내는 [Nullable](../nullable/) 개체의 기본 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| some | const T1\& | 첫 번째 비교값으로 사용할 값에 대한 상수 참조 |
| other | const [Nullable](../nullable/)\<T2\>\& | 두 번째 비교값으로 사용할 [Nullable](../nullable/) 개체가 나타내는 값에 대한 상수 참조 |

### 반환값

비교값이 같지 않으면 true, 그렇지 않으면 false

## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) 함수


두 스마트 포인터가 같지 않은지 비교합니다.

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| X | 첫 번째 포인터가 가리키는 유형 |
| Y | 두 번째 포인터가 가리키는 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | 비교할 첫 번째 포인터 |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | 비교할 두 번째 포인터 |

### 반환값

포인터가 일치하면 false, 그렇지 않으면 true.

## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) 함수


스마트 포인터가 null이 아닌지 확인합니다.

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| X | 포인터가 가리키는 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | 확인할 포인터 |

### 반환값

포인터가 null이면 false, 그렇지 않으면 true.

## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) 함수


스마트 포인터가 null이 아닌지 확인합니다.

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| X | 포인터가 가리키는 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | std::nullptr_t | 확인할 포인터 |

### 반환값

포인터가 null이면 false, 그렇지 않으면 true.

## System::operator!=(const SmartPtr\<X\>\&, const Y *) 함수


스마트 포인터와 단순 (C) 포인터의 부등호 비교.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| X | 스마트 포인터 유형 |
| Y | 단순 포인터 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | 비교할 스마트 포인터 (왼쪽) |
| y | const Y * | 비교할 포인터 (오른쪽) |

### 반환값

포인터가 일치하면 false, 그렇지 않으면 true.

## System::operator!=(const X *, const SmartPtr\<Y\>\&) 함수


스마트 포인터와 단순 (C) 포인터의 동등성 비교.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| X | 단순 포인터 유형 |
| Y | 스마트 포인터 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | const X * | 비교할 포인터 (오른쪽) |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | 비교할 스마트 포인터 (왼쪽) |

### 반환값

포인터가 일치하면 false, 그렇지 않으면 true.

## System::operator!=(Chars\&, const String\&) 함수


[String](../string/) 비교.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Chars | [String](../string/) 리터럴 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | Chars\& | 비교할 [String](../string/) 리터럴 |
| right | const [String](../string/)\& | 비교할 [String](../string/) |

### 반환값

문자열이 일치하면 false, 그렇지 않으면 true.

## System::operator!=(T\&, const String\&) 함수


[String](../string/) 비교.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [String](../string/) 포인터 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | T\& | 비교할 [String](../string/) 포인터 |
| right | const [String](../string/)\& | 비교할 [String](../string/) |

### 반환값

문자열이 일치하면 false, 그렇지 않으면 true.

## System::operator!=(const SharedPtr\<Object\>\&, const String\&) 함수


[Object](../object/) 및 문자열 비교.

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | 문자열로 변환하여 비교할 [Object](../object/) |
| right | const [String](../string/)\& | 비교할 [String](../string/) |

### 반환값

객체 문자열 표현이 문자열과 같으면 false, 그렇지 않으면 true.

## System::operator!=(std::nullptr_t, const String\&) 함수


문자열이 null인지 확인합니다.

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| str | std::nullptr_t | 확인할 [String](../string/) |

### 반환값

문자열이 null이면 false, 그렇지 않으면 true.

## System::operator!=(std::nullptr_t, TimeSpan) 함수




```cpp
constexpr bool System::operator!=(std::nullptr_t, TimeSpan)
```

## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) 함수


현재 및 지정된 개체가 나타내는 URI가 같지 않은지 확인합니다.

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | 비교할 첫 번째 [Uri](../uri/) 개체 |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | 비교할 두 번째 [Uri](../uri/) 개체 |

### 반환값

URI가 같지 않으면 true, 그렇지 않으면 false

## 참고

* Typedef [SharedPtr](../sharedptr/)
* 클래스 [ArraySegment](../arraysegment/)
* 클래스 [DateTime](../datetime/)
* 클래스 [DateTimeOffset](../datetimeoffset/)
* 클래스 [Nullable](../nullable/)
* 클래스 [SmartPtr](../smartptr/)
* 클래스 [Object](../object/)
* 클래스 [String](../string/)
* 클래스 [TimeSpan](../timespan/)
* 클래스 [Uri](../uri/)
* Struct [IsNullable](../isnullable/)
* 네임스페이스 [System](../)
* Library [Aspose.Slides](../../)