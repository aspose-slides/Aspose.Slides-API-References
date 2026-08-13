---
title: operator==()
second_title: Aspose.Slides for C++ API 참조
description: 
type: docs
weight: 2042
url: /ko/system/operator_equal_equal/
---
## System::operator==(ArraySegment\<T\>, ArraySegment\<T\>) function




```cpp
template<typename T> bool System::operator==(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator==(std::nullptr_t, DateTime) function




```cpp
constexpr bool System::operator==(std::nullptr_t, DateTime)
```

## System::operator==(std::nullptr_t, const DateTimeOffset\&) function




```cpp
constexpr bool System::operator==(std::nullptr_t, const DateTimeOffset &)
```

## System::operator==(std::nullptr_t, const Nullable\<T\>\&) function


Determines if the specified [Nullable](../nullable/) object represents a value that is equal to null.

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | std::nullptr_t | [Nullable](../nullable/) 객체에 대한 테스트용 상수 참조 |

### 반환값

True if the specified object represents null value, false otherwise

## System::operator==(const T1\&, const Nullable\<T2\>\&) function


Determines if the specified value is equal to the value represented by the specified [Nullable](../nullable/) object by applying [operator==()](./) to these values.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 첫 번째 비교값의 형식 |
| T2 | [Nullable](../nullable/) 객체가 나타내는 두 번째 비교값의 기본 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| some | const T1\& | 첫 번째 비교값으로 사용할 값에 대한 상수 참조 |
| other | const [Nullable](../nullable/)\<T2\>\& | [Nullable](../nullable/) 객체에 대한 상수 참조이며, 해당 객체가 나타내는 값은 두 번째 비교값으로 사용됩니다. |

### 반환값

True if the comparands are equal, otherwise - false

## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) function


Equal-compares two smart pointers.

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| X | 첫 번째 포인터가 가리키는 타입. |
| Y | 두 번째 포인터가 가리키는 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | 비교할 첫 번째 포인터. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | 비교할 두 번째 포인터. |

### 반환값

True if pointers match, false otherwise.

## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) function


Checks if smart pointer is null.

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| X | 포인터가 가리키는 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | std::nullptr_t | 확인할 포인터. |

### 반환값

True if pointer is null, false otherwise.

## System::operator==(const SmartPtr\<X\>\&, const Y *) function


Equality comparison smart pointer against simple (C) pointer.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| X | 스마트 포인터의 타입. |
| Y | 단순 포인터의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | 비교할 스마트 포인터(좌측). |
| y | const Y * | 비교할 포인터(우측). |

### 반환값

True if pointers match, false otherwise.

## System::operator==(const X *, const SmartPtr\<Y\>\&) function


Equality comparison smart pointer against simple (C) pointer.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| X | 단순 포인터의 타입. |
| Y | 스마트 포인터의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | const X * | 비교할 포인터(우측). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | 비교할 스마트 포인터(좌측). |

### 반환값

True if pointers match, false otherwise.

## System::operator==(T const\&, std::nullptr_t) function


Checks if value type object (translated C# structure, etc.) is null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 값 형식. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | T const\& | [Object](../object/) 확인. |

### 반환값

True if object is null, false otherwise.

## System::operator==(std::nullptr_t, T const\&) function


Checks if value type object (translated C# structure, etc.) is null.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 값 형식. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | std::nullptr_t | [Object](../object/) 확인. |

### 반환값

True if object is null, false otherwise.

## System::operator==(Chars\&, const String\&) function


[String](../string/) 비교.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Chars | [String](../string/) 리터럴 형식. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| left | Chars\& | 비교할 [String](../string/) 리터럴. |
| right | const [String](../string/)\& | 비교할 [String](../string/). |

### 반환값

true if strings match, false otherwise.

## System::operator==(T\&, const String\&) function


[String](../string/) 비교.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [String](../string/) 포인터 형식. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| left | T\& | 비교할 [String](../string/) 포인터. |
| right | const [String](../string/)\& | 비교할 [String](../string/). |

### 반환값

true if strings match, false otherwise.

## System::operator==(const SharedPtr\<Object\>\&, const String\&) function


[Object](../object/)와 문자열 비교.

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | 문자열로 변환하여 비교할 [Object](../object/). |
| right | const [String](../string/)\& | 비교할 [String](../string/). |

### 반환값

true if object string representation equals to string, false otherwise.

## System::operator==(std::nullptr_t, const String\&) function


Checks if string is null.

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | std::nullptr_t | 확인할 [String](../string/). |

### 반환값

true if string is null, false otherwise.

## System::operator==(std::nullptr_t, TimeSpan) function




```cpp
constexpr bool System::operator==(std::nullptr_t, TimeSpan)
```

## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) function


Determines if the URIs represented by the current and specified objects are equal.

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | 비교할 첫 번째 [Uri](../uri/) 객체 |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | 비교할 두 번째 [Uri](../uri/) 객체 |

### 반환값

True if URIs are equal, otherwise - false

## 참고

* Typedef [SharedPtr](../sharedptr/)
* Class [ArraySegment](../arraysegment/)
* Class [DateTime](../datetime/)
* Class [DateTimeOffset](../datetimeoffset/)
* Class [Nullable](../nullable/)
* Class [SmartPtr](../smartptr/)
* Class [Object](../object/)
* Class [String](../string/)
* Class [TimeSpan](../timespan/)
* Class [Uri](../uri/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)