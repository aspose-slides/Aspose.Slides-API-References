---
title: operator=()
second_title: Aspose.Slides C++ API referenciája
description: Áthelyezi a SmartPtr objektumot. x használhatatlanná válik.
type: docs
weight: 27
url: /hu/system/smartptr/operator_equal/
---
## SmartPtr::operator=(SmartPtr_\&&) metódus

Áthelyezi [SmartPtr](../) objektumot. x használhatatlanná válik.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Mutató a move-assign-hoz. |

### Visszatérési érték

Referencia erre az objektumra.

## SmartPtr::operator=(const SmartPtr_\&) metódus

Másolja és rendeli hozzá [SmartPtr](../) objektumot.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | Mutató a copy-assign-hoz. |

### Visszatérési érték

Referencia erre az objektumra.

## SmartPtr::operator=(const SmartPtr\<Q\>\&) metódus

Másolja és rendeli hozzá [SmartPtr](../) objektumot. A szükséges típuskonverziókat végzi.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Q | Az x által mutatott objektum típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | Mutató a copy-assign-hoz. |

### Visszatérési érték

Referencia erre az objektumra.

## SmartPtr::operator=(Pointee_ *) metódus

Nyers mutatót rendel hozzá [SmartPtr](../) objektumhoz.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| p | [Pointee_](../pointee_/) * | A hozzárendelendő mutató érték. |

### Visszatérési érték

Referencia erre az objektumra.

## SmartPtr::operator=(std::nullptr_t) metódus

A mutató értékét nullptr-ra állítja.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```

### Visszatérési érték

Referencia erre az objektumra.

## Lásd még

* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../pointee_/)
* Osztály [SmartPtr](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)