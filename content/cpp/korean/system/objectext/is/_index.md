---
title: Is()
second_title: Aspose.Slides for C++ API 레퍼런스
description: ‘is’ 연산자 변환을 구현합니다. 정확히 말하면 박스 가능(값) 타입에 대한 특수화입니다.
type: docs
weight: 92
url: /ko/system/objectext/is/
---
## ObjectExt::Is(const T\&) 메서드


'is' 연산자 변환을 구현합니다. 박스 가능(value) 타입에 대한 특수화이며 정확히는 해당 타입들입니다.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 대상 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) 'is' 연산자를 테스트하기 위한. 무시됩니다. |

### 반환값

항상 true

## ObjectExt::Is(const U\&) 메서드


'is' 연산자 변환을 구현합니다. 'final' 클래스를 위한 최적화된 포인터 타입 특수화.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 대상 타입. |
| U | 테스트 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) 'is' 연산자를 테스트하기 위한. |

### 반환값

‘is’가 true를 반환하면 true, 그렇지 않으면 false.

## ObjectExt::Is(const U\&) 메서드


'is' 연산자 변환을 구현합니다. 포인터 타입에 대한 특수화.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 대상 타입. |
| U | 테스트 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) 'is' 연산자를 테스트하기 위한. |

### 반환값

‘is’가 true를 반환하면 true, 그렇지 않으면 false.

## ObjectExt::Is(const Object\&) 메서드


'is' 연산자 변환을 구현합니다. 값 타입에 대한 특수화.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 대상 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) 'is' 연산자를 테스트하기 위한. |

### 반환값

‘is’가 true를 반환하면 true, 그렇지 않으면 false.

## ObjectExt::Is(const Object\&) 메서드


'is' 연산자 변환을 구현합니다. 변환 불가능한 타입에 대한 특수화.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 대상 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) 'is' 연산자를 테스트하기 위한. |

### 반환값

형식이 변환될 수 없으므로 항상 false를 반환합니다.

## ObjectExt::Is(const SmartPtr\<U\>\&) 메서드


'is' 연산자 변환을 구현합니다. 포인터 타입에 대한 특수화.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 대상 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) 'is' 연산자를 테스트하기 위한. |

### 반환값

‘is’가 true를 반환하면 true, 그렇지 않으면 false.

## ObjectExt::Is(const ExceptionWrapper\<U\>\&) 메서드


'is' 연산자 변환을 구현합니다. 예외 래퍼 타입에 대한 특수화.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 대상 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [ExceptionWrapper](../../exceptionwrapper/)\<U\>\& | [Object](../../object/) 'is' 연산자를 테스트하기 위한. |

### 반환값

‘is’가 true를 반환하면 true, 그렇지 않으면 false.

## ObjectExt::Is(const SmartPtr\<Object\>\&) 메서드


'is' 연산자 변환을 구현합니다. nullable 타입에 대한 특수화.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 대상 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) 'is' 연산자를 테스트하기 위한. |

### 반환값

‘is’가 true를 반환하면 true, 그렇지 않으면 false.

## ObjectExt::Is(const SmartPtr\<Object\>\&) 메서드


'is' 연산자 변환을 구현합니다. == 연산자가 정의된 박스 가능 타입에 대한 특수화.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 대상 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) 'is' 연산자를 테스트하기 위한. |

### 반환값

‘is’가 true를 반환하면 true, 그렇지 않으면 false.

## ObjectExt::Is(const SmartPtr\<Object\>\&) 메서드


'is' 연산자 변환을 구현합니다. == 연산자가 정의되지 않은 박스 가능 타입에 대한 특수화.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 대상 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) 'is' 연산자를 테스트하기 위한. |

### 반환값

‘is’가 true를 반환하면 true, 그렇지 않으면 false.

## ObjectExt::Is(const SmartPtr\<V\>\&) 메서드


'is' 연산자 변환을 구현합니다. 인터페이스에 박싱된 값 타입에 대한 특수화.

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 대상 타입. |
| V | 포인터가 가리키는 객체의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<V\>\& | [Object](../../object/) 'is' 연산자를 테스트하기 위한. |

### 반환값

‘is’가 true를 반환하면 true, 그렇지 않으면 false.

## ObjectExt::Is(const SmartPtr\<U\>\&) 메서드


'is' 연산자 변환을 구현합니다. 열거형 타입에 대한 특수화.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 대상 타입. |
| U | 포인터가 가리키는 객체의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) 'is' 연산자를 테스트하기 위한. |

### 반환값

‘is’가 true를 반환하면 true, 그렇지 않으면 false.

## ObjectExt::Is(const WeakPtr\<U\>\&) 메서드


'is' 연산자 변환을 구현합니다. 열거형 타입과 약한 포인터에 대한 특수화.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 대상 타입. |
| U | 포인터가 가리키는 객체의 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | const [WeakPtr](../../weakptr/)\<U\>\& | [Object](../../object/) 'is' 연산자를 테스트하기 위한. |

### 반환값

‘is’가 true를 반환하면 true, 그렇지 않으면 false.

## ObjectExt::Is(const Nullable\<U\>\&) 메서드


'is' 연산자 변환을 구현합니다. [Nullable](../../nullable/) 타입에 대한 특수화.

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 대상 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [Nullable](../../nullable/)\<U\>\& | [Nullable](../../nullable/) 타입. |

### 반환값

‘is’가 true를 반환하면 true, 그렇지 않으면 false.

## ObjectExt::Is(const char16_t *) 메서드


'is' 연산자 변환을 구현합니다. 문자열 리터럴에 대한 특수화.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 대상 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) 리터럴. |

### 반환값

‘is’가 true를 반환하면 true, 그렇지 않으면 false.

## ObjectExt::Is(int32_t) 메서드


'is' 연산자 변환을 구현합니다. 정수 리터럴에 대한 특수화.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 대상 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **int32_t** | 정수 리터럴. |

### 반환값

‘is’가 true를 반환하면 true, 그렇지 않으면 false.

## 관련 항목

* Class [ObjectExt](../)
* Class [Object](../../object/)
* Class [SmartPtr](../../smartptr/)
* Class [ExceptionWrapper](../../exceptionwrapper/)
* Class [WeakPtr](../../weakptr/)
* Class [Nullable](../../nullable/)
* Struct [IsBoxable](../../isboxable/)
* Struct [IsSmartPtr](../../issmartptr/)
* Struct [IsExceptionWrapper](../../isexceptionwrapper/)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)