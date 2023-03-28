---
title: operator=()
second_title: Aspose.Slides for C++ API Reference
description: Move-assigns smart pointer.
type: docs
weight: 27
url: /cpp/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=([SmartPtr_](../smartptr_/)\&&) method


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

## See Also

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DynamicWeakPtr::operator=(const [SmartPtr_](../smartptr_/)\&) method


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

## See Also

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DynamicWeakPtr::operator=(const [SmartPtr](../../smartptr/)\<Q\>\&) method


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

## See Also

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Class [SmartPtr](../../smartptr/)
* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DynamicWeakPtr::operator=(typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) *) method


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

## See Also

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [Pointee_](../../smartptr/pointee_/)
* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## DynamicWeakPtr::operator=(std::nullptr_t) method


Sets smart pointer to null.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```


### Return Value

Self reference.

## See Also

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Class [DynamicWeakPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
