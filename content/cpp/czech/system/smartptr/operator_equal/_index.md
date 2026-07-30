---
title: operator=()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Přiřazuje přesunutí objektu SmartPtr. x se stane nepoužitelným.
type: docs
weight: 27
url: /cs/system/smartptr/operator_equal/
---
## SmartPtr::operator=(SmartPtr_&&) metoda


Přiřazením přesunutím [SmartPtr](../) objektu. x se stane nepoužitelným.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Ukazatel pro přiřazení přesunutím. |

### Návratová hodnota

Odkaz na tento objekt.

## SmartPtr::operator=(const SmartPtr_&) metoda


Přiřazením kopie [SmartPtr](../) objektu.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | Ukazatel pro přiřazení kopií. |

### Návratová hodnota

Odkaz na tento objekt.

## SmartPtr::operator=(const SmartPtr<Q>&) metoda


Přiřazením kopie [SmartPtr](../) objektu. Provádí požadované konverze typů.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Q | Typ objektu, na který x ukazuje. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | const [SmartPtr](../)<Q>\& | Ukazatel pro přiřazení kopií. |

### Návratová hodnota

Odkaz na tento objekt.

## SmartPtr::operator=(Pointee_ *) metoda


Přiřadí surový ukazatel k [SmartPtr](../) objektu.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| p | [Pointee_](../pointee_/) * | Hodnota ukazatele k přiřazení. |

### Návratová hodnota

Odkaz na tento objekt.

## SmartPtr::operator=(std::nullptr_t) metoda


Nastaví hodnotu ukazatele na nullptr.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```


### Návratová hodnota

Odkaz na tento objekt.

## Viz také

* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../pointee_/)
* Třída [SmartPtr](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)