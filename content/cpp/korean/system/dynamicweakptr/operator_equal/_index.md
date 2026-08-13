---
title: operator=()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 스마트 포인터를 이동 할당합니다.
type: docs
weight: 27
url: /ko/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=(SmartPtr_\&&) 메서드

스마트 포인터를 이동 할당합니다.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | 이 이동 할당할 값을 가진 포인터. |

### 반환값

자기 참조.

## DynamicWeakPtr::operator=(const SmartPtr_&) 메서드

스마트 포인터를 복사 할당합니다.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | 복사 할당할 값을 가진 포인터. |

### 반환값

자기 참조.

## DynamicWeakPtr::operator=(const SmartPtr\<Q\>\&) 메서드

스마트 포인터를 복사 할당합니다.

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Q | 원본 포인터 타입. |

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | 복사 할당할 값을 가진 포인터. |

### 반환값

자기 참조.

## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) 메서드

스마트 포인터를 할당합니다.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| p | typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) * | 포인터 값. |

### 반환값

자기 참조.

## DynamicWeakPtr::operator=(std::nullptr_t) 메서드

스마트 포인터를 null로 설정합니다.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```

### 반환값

자기 참조.

## 참고

* 타입정의 [DynamicWeakPtr_](../dynamicweakptr_/)
* 타입정의 [SmartPtr_](../smartptr_/)
* 타입정의 [Pointee_](../../smartptr/pointee_/)
* 클래스 [DynamicWeakPtr](../)
* 클래스 [SmartPtr](../../smartptr/)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)