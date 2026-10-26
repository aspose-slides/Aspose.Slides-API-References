---
title: DynamicWeakPtr()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Tworzy pusty inteligentny wskaźnik.
type: docs
weight: 1
url: /pl/system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) konstruktor

Tworzy pusty inteligentny wskaźnik.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(std::nullptr_t=nullptr)
```

## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) konstruktor

Tworzy inteligentny wskaźnik wskazujący na podany obiekt.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | Obiekt wskazywany. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_&) konstruktor

Tworzy kopię inteligentnego wskaźnika.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Inteligentny wskaźnik, z którego kopiowane są informacje o obiekcie wskazywanym. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) konstruktor

Tworzy kopię inteligentnego wskaźnika.

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Q | Typ obiektu wskazywanego przez wskaźnik źródłowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Inteligentny wskaźnik, z którego kopiowane są informacje o obiekcie wskazywanym. |

## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_&) konstruktor

Tworzy kopię inteligentnego wskaźnika.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| ptr | const [DynamicWeakPtr_](../dynamicweakptr_/)\& | Inteligentny wskaźnik, z którego kopiowane są informacje o obiekcie wskazywanym. |

## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_&&) konstruktor

Konstruktor przenoszący inteligentny wskaźnik.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Inteligentny wskaźnik, z którego przenoszone są informacje o obiekcie wskazywanym. Staje się nieużyteczny po wywołaniu. |

## Zobacz także

* Definicja typu [Pointee_](../../smartptr/pointee_/)
* Definicja typu [SmartPtr_](../smartptr_/)
* Definicja typu [DynamicWeakPtr_](../dynamicweakptr_/)
* Klasa [DynamicWeakPtr](../)
* Klasa [SmartPtr](../../smartptr/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)