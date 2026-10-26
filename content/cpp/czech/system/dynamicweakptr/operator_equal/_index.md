---
title: operator=()
second_title: Aspose.Slides pro C++ API referenci
description: Přiřazuje chytrý ukazatel přesunem.
type: docs
weight: 27
url: /cs/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=(SmartPtr_\&&) metoda


Přiřazuje přesunem chytrý ukazatel.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Ukazatel, ze kterého se přesouvá hodnota při přiřazení. |

### Návratová hodnota

Odkaz na sebe.

## DynamicWeakPtr::operator=(const SmartPtr_\&) metoda


Kopíruje přiřazením chytrý ukazatel.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | Ukazatel, ze kterého se kopíruje hodnota při přiřazení. |

### Návratová hodnota

Odkaz na sebe.

## DynamicWeakPtr::operator=(const SmartPtr\<Q\>\&) metoda


Kopíruje přiřazením chytrý ukazatel.

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Q | Zdrojový typ ukazovaného objektu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Ukazatel, ze kterého se kopíruje hodnota při přiřazení. |

### Návratová hodnota

Odkaz na sebe.

## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) metoda


Přiřazuje chytrý ukazatel.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| p | typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) * | Hodnota ukazatele. |

### Návratová hodnota

Odkaz na sebe.

## DynamicWeakPtr::operator=(std::nullptr_t) metoda


Nastavuje chytrý ukazatel na null.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```


### Návratová hodnota

Odkaz na sebe.

## Viz také

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../../smartptr/pointee_/)
* Třída [DynamicWeakPtr](../)
* Třída [SmartPtr](../../smartptr/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)