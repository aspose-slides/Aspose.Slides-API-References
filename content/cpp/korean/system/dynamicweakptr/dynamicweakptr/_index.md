---
title: DynamicWeakPtr()
second_title: Aspose.Slides for C++ API 레퍼런스
description: null 스마트 포인터를 생성합니다.
type: docs
weight: 1
url: /ko/system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) 생성자

null 스마트 포인터를 생성합니다.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(std::nullptr_t=nullptr)
```

## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) 생성자

주어진 객체를 가리키는 스마트 포인터를 생성합니다.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | Pointee. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_\&) 생성자

스마트 포인터를 복사 생성합니다.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | 복사할 포인티 정보를 가진 스마트 포인터. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) 생성자

스마트 포인터를 복사 생성합니다.

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Q | 소스 포인터가 가리키는 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | 복사할 포인티 정보를 가진 스마트 포인터. |

## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_\&) 생성자

스마트 포인터를 복사 생성합니다.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ptr | const [DynamicWeakPtr_](../dynamicweakptr_/)\& | 복사할 포인티 정보를 가진 스마트 포인터. |

## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_\&&) 생성자

스마트 포인터를 이동 생성합니다.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | 포인티 정보를 이동할 스마트 포인터. 호출 후 사용할 수 없습니다. |

## 참고

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* 클래스 [DynamicWeakPtr](../)
* 클래스 [SmartPtr](../../smartptr/)
* 네임스페이스 [System](../../)
* Library [Aspose.Slides](../../../)