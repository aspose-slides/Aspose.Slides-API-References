---
title: operator=()
second_title: Aspose.Slides für C++ API-Referenz
description: Verschiebt den Smart Pointer.
type: docs
weight: 27
url: /de/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=(SmartPtr_\&&) Methode


Verschiebt den Smart Pointer.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Zeiger zum Verschieben des Zuweisungswertes. |

### Rückgabewert

Selbstreferenz.

## DynamicWeakPtr::operator=(const SmartPtr_\&) Methode


Kopiert den Smart Pointer.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | Zeiger zum Kopieren des Zuweisungswertes. |

### Rückgabewert

Selbstreferenz.

## DynamicWeakPtr::operator=(const SmartPtr\<Q\>\&) Methode


Kopiert den Smart Pointer.

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Q | Quell-Pointee-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Zeiger zum Kopieren des Zuweisungswertes. |

### Rückgabewert

Selbstreferenz.

## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) Methode


Weist den Smart Pointer zu.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| p | typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) * | Zeigerwert. |

### Rückgabewert

Selbstreferenz.

## DynamicWeakPtr::operator=(std::nullptr_t) Methode


Setzt den Smart Pointer auf null.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```


### Rückgabewert

Selbstreferenz.

## Siehe auch

* Typdefinition [DynamicWeakPtr_](../dynamicweakptr_/)
* Typdefinition [SmartPtr_](../smartptr_/)
* Typdefinition [Pointee_](../../smartptr/pointee_/)
* Klasse [DynamicWeakPtr](../)
* Klasse [SmartPtr](../../smartptr/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)