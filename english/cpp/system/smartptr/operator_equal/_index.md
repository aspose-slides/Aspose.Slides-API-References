---
title: operator=()
second_title: Aspose.Slides for C++ API Reference
description: Move-assigns SmartPtr object. x becomes unusable.
type: docs
weight: 27
url: /cpp/system/smartptr/operator_equal/
---
## SmartPtr::operator=(SmartPtr_\&&) method


Move-assigns [SmartPtr](../) object. x becomes unusable.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Pointer to move-assign. |

### Return Value

Reference to this object.

## SmartPtr::operator=(const SmartPtr_\&) method


Copy-assigns [SmartPtr](../) object.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | Pointer to copy-assign. |

### Return Value

Reference to this object.

## SmartPtr::operator=(const SmartPtr\<Q\>\&) method


Copy-assigns [SmartPtr](../) object. Does required type conversions.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Q | Type of object pointed by x. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | Pointer to copy-assign. |

### Return Value

Reference to this object.

## SmartPtr::operator=(Pointee_ *) method


Assigns raw pointer to [SmartPtr](../) object.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| p | [Pointee_](../pointee_/) * | Pointer value to assign. |

### Return Value

Reference to this object.

## SmartPtr::operator=(std::nullptr_t) method


Sets pointer value to nullptr.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```


### Return Value

Reference to this object.

## See Also

* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../pointee_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)