---
title: operator=()
second_title: Aspose.Slides for C++ API 레퍼런스
description: SmartPtr 객체를 이동 할당합니다. x는 사용할 수 없게 됩니다.
type: docs
weight: 27
url: /ko/system/smartptr/operator_equal/
---
## SmartPtr::operator=(SmartPtr_&&) 메서드


Move-assigns [SmartPtr](../) 객체. x는 사용할 수 없게 됩니다.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | move-assign용 포인터. |

### 반환 값

이 객체에 대한 참조.

## SmartPtr::operator=(const SmartPtr_&) 메서드


Copy-assigns [SmartPtr](../) 객체.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | copy-assign용 포인터. |

### 반환 값

이 객체에 대한 참조.

## SmartPtr::operator=(const SmartPtr\<Q\>\&) 메서드


Copy-assigns [SmartPtr](../) 객체. 필요한 형식 변환을 수행합니다.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```


### 템플릿 매개 변수

| Parameter | Description |
| --- | --- |
| Q | x가 가리키는 객체의 유형. |

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | copy-assign용 포인터. |

### 반환 값

이 객체에 대한 참조.

## SmartPtr::operator=(Pointee_ *) 메서드


[SmartPtr](../) 객체에 원시 포인터를 할당합니다.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| p | [Pointee_](../pointee_/) * | 할당할 포인터 값. |

### 반환 값

이 객체에 대한 참조.

## SmartPtr::operator=(std::nullptr_t) 메서드


포인터 값을 nullptr로 설정합니다.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```


### 반환 값

이 객체에 대한 참조.

## 또 보기

* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../pointee_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)