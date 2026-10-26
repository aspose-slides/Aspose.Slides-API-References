---
title: operator=()
second_title: Aspose.Slides voor C++ API Referentie
description: Voert een move-toewijzing uit op de slimme pointer.
type: docs
weight: 27
url: /nl/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=(SmartPtr_\&&) methode


Move-assigns smart pointer.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Pointer waarvan de move-assign-waarde wordt gehaald. |

### Retourwaarde

Zelfreferentie.

## DynamicWeakPtr::operator=(const SmartPtr_\&) methode


Copy-assigns smart pointer.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | Pointer waarvan de copy-assign-waarde wordt gehaald. |

### Retourwaarde

Zelfreferentie.

## DynamicWeakPtr::operator=(const SmartPtr\<Q\>\&) methode


Copy-assigns smart pointer.

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| Q | Source pointee type. |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Pointer waarvan de copy-assign-waarde wordt gehaald. |

### Retourwaarde

Zelfreferentie.

## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) methode


Assigns smart pointer.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| p | typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) * | Pointer-waarde. |

### Retourwaarde

Zelfreferentie.

## DynamicWeakPtr::operator=(std::nullptr_t) methode


Sets smart pointer to null.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```


### Retourwaarde

Zelfreferentie.

## Zie ook

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../../smartptr/pointee_/)
* Klasse [DynamicWeakPtr](../)
* Klasse [SmartPtr](../../smartptr/)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)