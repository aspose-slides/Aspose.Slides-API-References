---
title: operator=()
second_title: Aspose.Slides C++ API referenciája
description: Áthelyezi az okos mutatót.
type: docs
weight: 27
url: /hu/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=(SmartPtr_&&) metódus


Áthelyezi az okos mutatót.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Pointer to move-assign value from. |

### Visszatérési érték

Saját referencia.

## DynamicWeakPtr::operator=(const SmartPtr_&) metódus


Másolja az okos mutatót.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | Pointer to copy-assign value from. |

### Visszatérési érték

Saját referencia.

## DynamicWeakPtr::operator=(const SmartPtr\<Q\>\&) metódus


Másolja az okos mutatót.

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Q | Source pointee type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Pointer to copy-assign value from. |

### Visszatérési érték

Saját referencia.

## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) metódus


Beállítja az okos mutatót.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| p | typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) * | Pointer value. |

### Visszatérési érték

Saját referencia.

## DynamicWeakPtr::operator=(std::nullptr_t) metódus


Beállítja az okos mutatót nullára.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```


### Visszatérési érték

Saját referencia.

## Lásd még

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../../smartptr/pointee_/)
* Class [DynamicWeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)