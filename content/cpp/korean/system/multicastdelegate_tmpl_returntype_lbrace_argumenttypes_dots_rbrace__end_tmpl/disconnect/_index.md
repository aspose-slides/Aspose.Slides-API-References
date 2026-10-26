---
title: disconnect()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 delegate를 delegate 컬렉션에서 제거합니다.
type: docs
weight: 170
url: /ko/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) method

지정된 delegate를 delegate 컬렉션에서 제거합니다.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| callback | [Callback](../callback/) | 컬렉션에서 제거할 delegate |

### 반환값

self에 대한 참조

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) method

지정된 객체의 지정된 비정적 메서드를 delegate 컬렉션에서 제거합니다.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| MemberType | 컬렉션에서 제거할 비정적 메서드의 유형 |
| ClassType | 컬렉션에서 제거할 객체 메서드의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| member | MemberType ClassType::* | 지정된 객체의 비정적 메서드에 대한 포인터 |
| obj | ClassType * | 컬렉션에서 제거할 객체 멤버 메서드에 대한 포인터 |

### 반환값

self에 대한 참조

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) method

지정된 객체의 지정된 비정적 메서드를 delegate 컬렉션에서 제거합니다.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| MemberType | 컬렉션에서 제거할 비정적 메서드의 유형 |
| ClassType | 컬렉션에서 제거할 객체 메서드의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| member | MemberType ClassType::* | 지정된 객체의 비정적 메서드에 대한 포인터 |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | 컬렉션에서 제거할 객체 멤버 메서드에 대한 공유 포인터 |

### 반환값

self에 대한 참조

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) method

지정된 MulticastDelegate 객체를 delegate 컬렉션에서 제거합니다.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | 컬렉션에서 제거할 MulticastDelegate 클래스 인스턴스 |

### 반환값

self에 대한 참조

## 참고

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)