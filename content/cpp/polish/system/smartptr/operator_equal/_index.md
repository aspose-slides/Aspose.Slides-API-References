---
title: operator=()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Przypisuje przeniesieniem obiekt SmartPtr. x staje się nieużywalny.
type: docs
weight: 27
url: /pl/system/smartptr/operator_equal/
---
## SmartPtr::operator=(SmartPtr_\&&) metoda


Przypisuje przeniesienie [SmartPtr](../) obiektu. x staje się nieużywalny.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Wskaźnik do przypisania przeniesieniem. |

### Wartość zwracana

Odniesienie do tego obiektu.

## SmartPtr::operator=(const SmartPtr_\&) metoda


Przypisuje kopiowanie [SmartPtr](../) obiektu.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | Wskaźnik do przypisania kopiowaniem. |

### Wartość zwracana

Odniesienie do tego obiektu.

## SmartPtr::operator=(const SmartPtr\<Q\>\&) metoda


Przypisuje kopiowanie [SmartPtr](../) obiektu. Wykonuje wymagane konwersje typów.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Q | Typ obiektu wskazywanego przez x. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | Wskaźnik do przypisania kopiowaniem. |

### Wartość zwracana

Odniesienie do tego obiektu.

## SmartPtr::operator=(Pointee_ *) metoda


Przypisuje surowy wskaźnik do [SmartPtr](../) obiektu.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| p | [Pointee_](../pointee_/) * | Wartość wskaźnika do przypisania. |

### Wartość zwracana

Odniesienie do tego obiektu.

## SmartPtr::operator=(std::nullptr_t) metoda


Ustawia wartość wskaźnika na nullptr.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```


### Wartość zwracana

Odniesienie do tego obiektu.

## Zobacz także

* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../pointee_/)
* Klasa [SmartPtr](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)