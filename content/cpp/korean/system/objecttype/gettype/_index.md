---
title: GetType()
second_title: Aspose.Slides for C++ API 레퍼런스
description: typeof() 변환을 구현합니다. 스마트 포인터에 대한 오버로드.
type: docs
weight: 1
url: /ko/system/objecttype/gettype/
---
## ObjectType::GetType(const T\&) 메서드

typeof() 변환을 구현합니다. 스마트 포인터에 대한 오버로드.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Pointer object type. |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/)를 [TypeInfo](../../typeinfo/)에 대해 얻기 위해. |

### 반환 값

전달된 객체의 최종 클래스를 설명하는 [TypeInfo](../../typeinfo/) 구조체에 대한 const 레퍼런스입니다.

## ObjectType::GetType(const T\&) 메서드

typeof() 변환을 구현합니다. 구조체에 대한 오버로드.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Structure type. |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/)를 [TypeInfo](../../typeinfo/)에 대해 얻기 위해. |

### 반환 값

전달된 객체의 최종 클래스를 설명하는 [TypeInfo](../../typeinfo/) 구조체에 대한 const 레퍼런스입니다.

## ObjectType::GetType(const T\&) 메서드

typeof() 변환을 구현합니다. 예외에 대한 오버로드.

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Exception type. |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/)를 [TypeInfo](../../typeinfo/)에 대해 얻기 위해. |

### 반환 값

전달된 객체의 최종 클래스를 설명하는 [TypeInfo](../../typeinfo/) 구조체에 대한 const 레퍼런스입니다.

## ObjectType::GetType(const T) 메서드

typeof() 변환을 구현합니다. 원시 타입에 대한 오버로드.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Primitive type. |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| obj | const T | 무시됨 |

### 반환 값

전달된 객체의 타입을 설명하는 [TypeInfo](../../typeinfo/) 구조체에 대한 const 레퍼런스입니다.

## ObjectType::GetType(const T) 메서드

typeof() 변환을 구현합니다. [Nullable](../../nullable/) 타입에 대한 오버로드.

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Nullable](../../nullable/) type. |

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| obj | const T | 무시됨 |

### 반환 값

전달된 객체의 타입을 설명하는 [TypeInfo](../../typeinfo/) 구조체에 대한 const 레퍼런스입니다.

## ObjectType::GetType() 메서드

typeof() 변환을 구현합니다. 원시 타입에 대한 오버로드.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Primitive type. |

### 반환 값

지정된 타입을 설명하는 [TypeInfo](../../typeinfo/) 구조체에 대한 const 레퍼런스입니다.

## ObjectType::GetType() 메서드

typeof() 변환을 구현합니다. 열거형 타입에 대한 오버로드.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Primitive type. |

### 반환 값

지정된 타입을 설명하는 [TypeInfo](../../typeinfo/) 구조체에 대한 const 레퍼런스입니다.

## ObjectType::GetType() 메서드

typeof() 변환을 구현합니다. 구조체 및 포인터에 대한 오버로드.

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Primitive type. |

### 반환 값

지정된 구조를 설명하는 [TypeInfo](../../typeinfo/) 구조체에 대한 const 레퍼런스입니다.

## ObjectType::GetType() 메서드

typeof() 변환을 구현합니다. [Nullable](../../nullable/)에 대한 오버로드.

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | [Nullable](../../nullable/) type. |

### 반환 값

지정된 구조를 설명하는 [TypeInfo](../../typeinfo/) 구조체에 대한 const 레퍼런스입니다.

## ObjectType::GetType() 메서드

typeof() 변환을 구현합니다. MutlicastDelegate에 대한 오버로드.

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | MutlicastDelegate type. |

### 반환 값

지정된 구조를 설명하는 [TypeInfo](../../typeinfo/) 구조체에 대한 const 레퍼런스입니다.

## ObjectType::GetType() 메서드

typeof() 변환을 구현합니다. 구조체 및 포인터에 대한 오버로드.

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Primitive type. |

### 반환 값

[SmartPtr](../../smartptr/)에 대해 호출된 경우, 지정된 구조 또는 포인터가 가리키는 타입을 설명하는 [TypeInfo](../../typeinfo/) 구조체에 대한 const 레퍼런스입니다.

## ObjectType::GetType(const String\&) 메서드

typeof() 변환을 구현합니다. 문자열 타입에 대한 오버로드.

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | Primitive type. |

### 반환 값

[String](../../string/) 타입을 설명하는 [TypeInfo](../../typeinfo/) 구조체에 대한 const 레퍼런스입니다.

## ObjectType::GetType() 메서드

typeof() 변환을 구현합니다. **uint8_t**에 대한 오버로드.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() 메서드

typeof() 변환을 구현합니다. char16_t에 대한 오버로드.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() 메서드

typeof() 변환을 구현합니다. **int32_t**에 대한 오버로드.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() 메서드

typeof() 변환을 구현합니다. **int64_t**에 대한 오버로드.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() 메서드

typeof() 변환을 구현합니다. bool에 대한 오버로드.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() 메서드

typeof() 변환을 구현합니다. [Void](../../void/)에 대한 오버로드.

```cpp
const System::TypeInfo & System::ObjectInfo::GetType()
```

## 참조

* 클래스 [ObjectType](../)
* 클래스 [TypeInfo](../../typeinfo/)
* 클래스 [String](../../string/)
* 구조체 [IsSmartPtr](../../issmartptr/)
* 구조체 [IsExceptionWrapper](../../isexceptionwrapper/)
* 구조체 [IsNullable](../../isnullable/)
* 구조체 [IsBoxable](../../isboxable/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)