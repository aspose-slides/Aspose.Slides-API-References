---
title: MakeSharedPtr()
second_title: Aspose.Slides dla C++ referencja API
description: Konwertuje surowy wskaźnik na inteligentny wskaźnik.
type: docs
weight: 2900
url: /pl/system/makesharedptr/
---
## System::MakeSharedPtr(X *) funkcja


Konwertuje surowy wskaźnik na inteligentny wskaźnik.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(X *p)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| X | Typ elementu. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| p | X * | Surowy wskaźnik do obiektu. |

### Wartość zwracana

Inteligentny wskaźnik współdzielony do obiektu.

## System::MakeSharedPtr(const X *) funkcja


Konwertuje surowy wskaźnik na inteligentny wskaźnik. Przeciążenie dla stałych wskaźników. Przydatne np. przy używaniu zmiennej 'this' w metodach C# tłumaczonych jako const.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(const X *p)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| X | Typ elementu. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| p | const X * | Surowy wskaźnik do obiektu. |

### Wartość zwracana

Inteligentny wskaźnik współdzielony do obiektu.

## Zobacz także

* Klasa [SmartPtr](../smartptr/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)