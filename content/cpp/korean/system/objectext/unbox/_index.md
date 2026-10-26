---
title: Unbox()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Object 로 변환한 후 값 타입을 언박스합니다. 열거형 타입에 대한 구현입니다.
type: docs
weight: 53
url: /ko/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) 메서드


[Object](../../object/)(으)로 변환한 후 값 타입을 언박스합니다. 열거형 타입에 대한 구현입니다.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Enum](../../enum/) 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | 언박스할 [Object](../../object/). |

### 반환 값

[Enum](../../enum/) 값.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) 메서드


[Object](../../object/)(으)로 변환한 후 값 타입을 언박스합니다. 열거형이 아니며 nullable도 아닌 타입에 대한 구현입니다.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Value type. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | 언박스할 [Object](../../object/). |

### 반환 값

언박스된 값.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) 메서드


[Object](../../object/)(으)로 변환한 후 값 타입을 언박스합니다. 열거형이 아니며 nullable도 아닌 타입에 대한 구현입니다.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Value type. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | 언박스할 [Object](../../object/). |

### 반환 값

언박스된 값.

## ObjectExt::Unbox(E) 메서드


열거형 타입을 정수로 언박스합니다.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 대상 정수 타입. |
| E | 소스 열거형 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| e | E | 언박스할 값. |

### 반환 값

열거형의 정수 표현.

## ObjectExt::Unbox(E) 메서드


열거형 타입을 변환합니다.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 대상 열거형 타입. |
| E | 소스 열거형 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| e | E | 언박스할 값. |

### 반환 값

변환된 열거형 값.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) 메서드


문자열 값을 언박스합니다.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | 언박스할 [Object](../../object/) |

### 반환 값

[String](../../string/) 표현, 박싱된 문자열이 null인 경우 null일 수 있습니다.

## 참조

* 클래스 [SmartPtr](../../smartptr/)
* 클래스 [Object](../../object/)
* 클래스 [ObjectExt](../)
* 클래스 [String](../../string/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)