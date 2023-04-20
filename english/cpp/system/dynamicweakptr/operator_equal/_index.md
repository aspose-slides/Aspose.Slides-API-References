---
title: operator=()
second_title: Aspose.Slides for C++ API Reference
description: Move-assigns smart pointer.
type: docs
weight: 27
url: /cpp/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=(SmartPtr_\&&) method


Move-assigns smart pointer.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Pointer to move-assign value from. |

### Return Value

Self reference.

## DynamicWeakPtr::operator=(const SmartPtr_\&) method


Copy-assigns smart pointer.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | Pointer to copy-assign value from. |

### Return Value

Self reference.

## DynamicWeakPtr::operator=(const SmartPtr\<Q\>\&) method


Copy-assigns smart pointer.

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Q | Source pointee type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Pointer to copy-assign value from. |

### Return Value

Self reference.

## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) method


Assigns smart pointer.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| p | typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) * | Pointer value. |

### Return Value

Self reference.

## DynamicWeakPtr::operator=(std::nullptr_t) method


Sets smart pointer to null.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```


### Return Value

Self reference.

## See Also

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../../smartptr/pointee_/)
* Class [DynamicWeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)