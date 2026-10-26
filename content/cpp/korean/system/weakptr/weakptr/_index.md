---
title: WeakPtr()
second_title: Aspose.Slides for C++ API 참조
description: null 포인터를 생성합니다.
type: docs
weight: 1
url: /ko/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(std::nullptr_t) 생성자

null 포인터를 생성합니다.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## WeakPtr::WeakPtr(Pointee_ *) 생성자

주어진 객체에 대한 약한 포인터를 생성합니다.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | [Object](../../object/) 약한 포인터를 생성하기 위한 |

## WeakPtr::WeakPtr(const SmartPtr_\&) 생성자

ptr이 가리키는 동일한 포인터를 참조하는 약한 포인터를 생성합니다.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ptr | const [SmartPtr_](../../smartptr/smartptr_/)\& | 복사할 pointee 값을 가져올 포인터. |

## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) 생성자

x가 가리키는 동일한 포인터를 참조하는 약한 포인터를 생성합니다.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Q | 소스 포인터의 pointee 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | 복사할 pointee 값을 가져올 포인터. |

## WeakPtr::WeakPtr(const WeakPtr_\&) 생성자

약한 포인터를 복사 생성합니다.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ptr | const [WeakPtr_](../weakptr_/)\& | 복사할 pointee 값을 가져올 포인터. |

## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) 생성자

약한 포인터를 복사 생성합니다.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| Q | 소스 pointee 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | const [WeakPtr](../)\<Q\>\& | 복사할 pointee 값을 가져올 포인터. |

## WeakPtr::WeakPtr(SmartPtr_\&&) 생성자

약한 포인터를 이동 생성합니다.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | [SmartPtr_](../../smartptr/smartptr_/)\&& | pointee 값을 이동할 포인터. |

## 참고

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../../smartptr/smartptr_/)
* Typedef [WeakPtr_](../weakptr_/)
* Class [WeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)