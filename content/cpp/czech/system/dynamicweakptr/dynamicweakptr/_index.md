---
title: DynamicWeakPtr()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří nulový chytrý ukazatel.
type: docs
weight: 1
url: /cs/system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) konstruktor

Vytvoří nulový chytrý ukazatel.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(std::nullptr_t=nullptr)
```

## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) konstruktor

Vytvoří chytrý ukazatel ukazující na zadaný objekt.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | Ukazovaný objekt. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_\&) konstruktor

Kopíruje konstrukci chytrého ukazatele.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Chytrý ukazatel, ze kterého se kopírují informace o ukazovaném objektu. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) konstruktor

Kopíruje konstrukci chytrého ukazatele.

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Q | Typ ukazovaného objektu zdrojového ukazatele. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Chytrý ukazatel, ze kterého se kopírují informace o ukazovaném objektu. |

## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_\&) konstruktor

Kopíruje konstrukci chytrého ukazatele.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ptr | const [DynamicWeakPtr_](../dynamicweakptr_/)\& | Chytrý ukazatel, ze kterého se kopírují informace o ukazovaném objektu. |

## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_\&&) konstruktor

Přesune konstrukci chytrého ukazatele.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Chytrý ukazatel, ze kterého se přesouvají informace o ukazovaném objektu. Stane se po volání nepoužitelným. |

## Viz také

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Třída [DynamicWeakPtr](../)
* Třída [SmartPtr](../../smartptr/)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)