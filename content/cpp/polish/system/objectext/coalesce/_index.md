---
title: Coalesce()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Implementacja tłumaczenia operatora '??' dla typów nie-nullowalnych.
type: docs
weight: 170
url: /pl/system/objectext/coalesce/
---
## ObjectExt::Coalesce(T0, T1) metoda

Implementacja operatora '??' dla typów nie-nullowalnych.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T0 | Typ wartości LHS. |
| T1 | Typ lambdy obejmującej wyrażenie RHS. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | T0 | Wartość LHS. |
| func | T1 | Wyrażenie RHS. |

### Wartość zwracana

Jeśli wartość LHS nie jest nullem, zwraca LHS, w przeciwnym razie oblicza wyrażenie RHS i zwraca wynik.

## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) metoda

Implementacja operatora '??' dla typów nullowalnych.

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T0 | Typ wartości LHS. |
| T1 | Typ lambdy obejmującej wyrażenie RHS. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [System::Nullable](../../nullable/)\<T0\> | Wartość LHS. |
| func | T1 | Wyrażenie RHS. |

### Wartość zwracana

Jeśli wartość LHS nie jest nullem, zwraca LHS, w przeciwnym razie oblicza wyrażenie RHS i zwraca wynik.

## Zobacz również

* Klasa [ObjectExt](../)
* Klasa [Nullable](../../nullable/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)