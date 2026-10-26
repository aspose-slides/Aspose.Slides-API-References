---
title: operator=()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Przypisuje wskaźnik inteligentny przy przeniesieniu.
type: docs
weight: 27
url: /pl/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=(SmartPtr_\&&) metoda

Przypisuje wskaźnik inteligentny przy przeniesieniu.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Wskaźnik, z którego pobiera się wartość do przypisania przy przeniesieniu. |

### Wartość zwracana

Odwołanie do siebie.

## DynamicWeakPtr::operator=(const SmartPtr_\&) metoda

Przypisuje wskaźnik inteligentny poprzez kopiowanie.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | Wskaźnik, z którego pobiera się wartość do kopiującego przypisania. |

### Wartość zwracana

Odwołanie do siebie.

## DynamicWeakPtr::operator=(const SmartPtr\<Q\>\&) metoda

Przypisuje wskaźnik inteligentny poprzez kopiowanie.

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Q | Typ elementu źródłowego. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Wskaźnik, z którego pobiera się wartość do kopiującego przypisania. |

### Wartość zwracana

Odwołanie do siebie.

## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) metoda

Przypisuje wskaźnik inteligentny.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| p | typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) * | Wartość wskaźnika. |

### Wartość zwracana

Odwołanie do siebie.

## DynamicWeakPtr::operator=(std::nullptr_t) metoda

Ustawia wskaźnik inteligentny na null.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```

### Wartość zwracana

Odwołanie do siebie.

## Zobacz także

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../../smartptr/pointee_/)
* Klasa [DynamicWeakPtr](../)
* Klasa [SmartPtr](../../smartptr/)
* Przestrzeń nazw [System](../../)
* Library [Aspose.Slides](../../../)