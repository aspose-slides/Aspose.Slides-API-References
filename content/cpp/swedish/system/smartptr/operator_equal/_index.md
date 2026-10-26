---
title: operator=()
second_title: Aspose.Slides för C++ API-referens
description: Utför move-tilldelning av SmartPtr-objekt. x blir oanvändbar.
type: docs
weight: 27
url: /sv/system/smartptr/operator_equal/
---
## SmartPtr::operator=(SmartPtr_&&) metod


Utför move-tilldelning av [SmartPtr](../)-objekt. x blir oanvändbar.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)&& | Pekare för move-tilldelning. |

### Return Value

Referens till detta objekt.

## SmartPtr::operator=(const SmartPtr_&) metod


Utför copy-tilldelning av [SmartPtr](../)-objekt.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)& | Pekare för copy-tilldelning. |

### Return Value

Referens till detta objekt.

## SmartPtr::operator=(const SmartPtr\<Q\>&) metod


Utför copy-tilldelning av [SmartPtr](../)-objekt. Utför nödvändiga typkonverteringar.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Q | Typ av objekt som pekas på av x. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>& | Pekare för copy-tilldelning. |

### Return Value

Referens till detta objekt.

## SmartPtr::operator=(Pointee_ *) metod


Tilldelar rå pekare till [SmartPtr](../)-objekt.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| p | [Pointee_](../pointee_/) * | Pekarvärde att tilldela. |

### Return Value

Referens till detta objekt.

## SmartPtr::operator=(std::nullptr_t) metod


Sätter pekarvärdet till nullptr.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```


### Return Value

Referens till detta objekt.

## Se också

* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../pointee_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)