---
title: connect()
second_title: Aspose.Slides C++용 API 참조
description: 지정된 대리자를 컬렉션에 추가합니다.
type: docs
weight: 144
url: /ko/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) method


지정된 대리자를 컬렉션에 추가합니다.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| callback | [Callback](../callback/) | 컬렉션에 추가할 대리자 |

### 반환값

self에 대한 참조

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) method


지정된 함수 객체를 대리자 컬렉션에 추가합니다. 함수 객체는 컬렉션에 추가되기 전에 Callback 대리자 유형으로 변환됩니다.

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| R | 컬렉션에 추가할 함수 객체의 반환 유형 |
| Args | 컬렉션에 추가할 함수 객체의 인수 목록 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| f | std::function\<R(Args...)> | 컬렉션에 추가할 함수 객체 |

### 반환값

self에 대한 참조

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) method


지정된 MulticastDelegate 객체를 대리자 컬렉션에 추가합니다.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | 컬렉션에 추가할 MulticastDelegate 클래스의 인스턴스 |

### 반환값

self에 대한 참조

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) method


지정된 객체의 지정된 비정적 메서드를 대리자 컬렉션에 추가합니다.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| MemberType | 컬렉션에 추가될 비정적 메서드의 유형 |
| ClassType | 컬렉션에 추가될 객체 메서드의 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| member | MemberType ClassType::* | 지정된 객체의 비정적 메서드에 대한 포인터 |
| obj | ClassType * | 컬렉션에 추가될 객체 멤버 메서드에 대한 포인터 |

### 반환값

self에 대한 참조

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) method


지정된 객체의 지정된 비정적 메서드를 대리자 컬렉션에 추가합니다.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| MemberType | 컬렉션에 추가될 비정적 메서드의 유형 |
| ClassType | 컬렉션에 추가될 객체 메서드의 유형 |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| member | MemberType ClassType::* | 지정된 객체의 비정적 메서드에 대한 포인터 |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | 컬렉션에 추가될 객체 멤버 메서드에 대한 공유 포인터 |

### 반환값

self에 대한 참조

## 참고

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)