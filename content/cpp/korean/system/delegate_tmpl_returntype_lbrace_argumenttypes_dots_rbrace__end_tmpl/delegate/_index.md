---
title: Delegate()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 기본 생성자. 아무것도 가리키지 않는 delegate 객체를 생성합니다.
type: docs
weight: 1
url: /ko/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() 메서드

기본 생성자. 아무것도 가리키지 않는 delegate 객체를 생성합니다.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) 메서드

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) 메서드

이동 복사 생성자. 지정된 delegate가 가리키는 엔티티의 소유권을 획득합니다.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| o | Delegate\&& | 이동할 엔티티를 가리키는 Delegate 객체 |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) 메서드

생성자. 지정된 자유 함수 또는 정적 메서드 포인터에서 delegate 객체를 생성합니다.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| The | 생성자가 인수로 받아들이는 함수 또는 정적 메서드 포인터의 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| function | T | 새로 만든 Delegate 인스턴스가 가리키게 될 함수 또는 정적 메서드 포인터 |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) 메서드

생성자. std::bind() 로 생성된 함수 객체 포인터에서 delegate 를 생성합니다.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| The | 생성자가 인수로 받아들이는 std::bind() 로 생성된 함수 객체의 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| function | T | 새로 만든 Delegate 인스턴스가 가리키게 될 “bind expression”—std::bind() 로 생성된 함수 포인터 |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) 메서드

생성자. 지정된 함수 객체에서 delegate 를 생성합니다.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 생성자가 인수로 받아들이는 함수 객체의 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| functor_tag | int | 모호성을 해소하기 위해 사용되는 더미 정수 값 |
| functor | T\& | 새로 만든 delegate 가 가리키게 될 함수 객체 |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) 메서드

이동 생성자. 지정된 함수 객체에서 delegate 를 생성합니다.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 생성자가 인수로 받아들이는 함수 객체의 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| functor_tag | long | 모호성을 해소하기 위해 사용되는 더미 정수 값 |
| functor | T\&& | 새로 만든 delegate 가 가리키게 될 함수 객체 |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) 메서드

생성자. 지정된 객체의 비정적 메서드를 가리키는 delegate 를 생성합니다.

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| MemberType | 생성자가 인수로 받아들이는 비정적 메서드의 형식 |
| ClassType | 생성자가 인수로 받아들이는 객체의 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| member | MemberType ClassType::* | 새로 만든 delegate 가 가리키게 될 비정적 메서드 포인터 |
| obj | ClassType * | 새로 만든 delegate 가 가리키게 될 객체 멤버 메서드 포인터 |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) 메서드

생성자. 지정된 객체의 비정적 메서드를 가리키는 delegate 를 생성합니다.

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| MemberType | 생성자가 인수로 받아들이는 비정적 메서드의 형식 |
| ClassType | 생성자가 인수로 받아들이는 객체의 형식 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| member | MemberType MemberClass::* | 새로 만든 delegate 가 가리키게 될 비정적 메서드 포인터 |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | 새로 만든 delegate 가 가리키게 될 객체 멤버 메서드에 대한 공유 포인터 |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) 메서드

std::function 함수 객체를 가리키는 delegate 객체를 생성합니다.

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| R | 생성자가 인수로 받아들이는 함수 객체의 반환 형식 |
| Args | 생성자가 인수로 받아들이는 함수 객체의 매개변수 목록 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| f | std::function\<R(Args...)> | 새로 만든 delegate 객체가 가리키게 될 함수 객체 |

## 참조

* Typedef [SharedPtr](../../sharedptr/)
* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)