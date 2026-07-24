---
title: DynamicWeakPtr()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen Null-Smart-Pointer.
type: docs
weight: 1
url: /de/system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) Konstruktor

Erstellt einen Null Smart-Pointer.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(std::nullptr_t=nullptr)
```

## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) Konstruktor

Erstellt einen Smart-Pointer, der auf das angegebene Objekt zeigt.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | Pointee. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_\&) Konstruktor

Kopiert einen Smart-Pointer.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Smart-Pointer, von dem die Pointee-Informationen kopiert werden. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) Konstruktor

Kopiert einen Smart-Pointer.

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Q | Quellzeiger-Pointee-Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Smart-Pointer, von dem die Pointee-Informationen kopiert werden. |

## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_\&) Konstruktor

Kopiert einen Smart-Pointer.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ptr | const [DynamicWeakPtr_](../dynamicweakptr_/)\& | Smart-Pointer, von dem die Pointee-Informationen kopiert werden. |

## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_\&&) Konstruktor

Konstruiert einen Smart-Pointer durch Move.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Smart-Pointer, von dem die Pointee-Informationen verschoben werden. Wird nach dem Aufruf unbrauchbar. |

## Siehe auch

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Class [DynamicWeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)