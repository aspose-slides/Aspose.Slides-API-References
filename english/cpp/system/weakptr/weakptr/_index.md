---
title: WeakPtr()
second_title: Aspose.Slides for C++ API Reference
description: Creates null pointer.
type: docs
weight: 1
url: /cpp/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(std::nullptr_t) constructor


Creates null pointer.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## WeakPtr::WeakPtr(Pointee_ *) constructor


Creates weak pointer to given object.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | [Object](../../object/) to create weak pointer to. |

## WeakPtr::WeakPtr(const SmartPtr_\&) constructor


Creates weak pointer referencing same pointer ptr points to.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const [SmartPtr_](../../smartptr/smartptr_/)\& | Pointer to copy pointee value from. |

## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) constructor


Creates weak pointer referencing same pointer x points to.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Q | Pointee type of source pointer. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Pointer to copy pointee value from. |

## WeakPtr::WeakPtr(const WeakPtr_\&) constructor


Copy-constructs weak pointer.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const [WeakPtr_](../weakptr_/)\& | Pointer to copy pointee value from. |

## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) constructor


Copy-constructs weak pointer.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Q | Source pointee type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [WeakPtr](../)\<Q\>\& | Pointer to copy pointee value from. |

## WeakPtr::WeakPtr(SmartPtr_\&&) constructor


Move-constructs weak pointer.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | [SmartPtr_](../../smartptr/smartptr_/)\&& | Pointer to move pointee value from. |

## See Also

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../../smartptr/smartptr_/)
* Typedef [WeakPtr_](../weakptr_/)
* Class [WeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)