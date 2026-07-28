---
title: CoalesceAssign()
second_title: Aspose.Slides dla C++ - referencja API
description: Implementacja tłumaczenia operatora '??='.
type: docs
weight: 183
url: /pl/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign(T0\&, T1) metoda

Implementacja tłumaczenia operatora '??='.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::CoalesceAssign(T0 &value, T1 func) -> T0 &
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T0 | typ wartości LHS. |
| T1 | typ lambdy enkapsulującej wyrażenie RHS. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | T0\& | wartość LHS. |
| func | T1 | wyrażenie RHS. |

### Wartość zwracana

Jeśli wartość LHS nie jest null, zwraca LHS, w przeciwnym razie oblicza wyrażenie RHS i zwraca wynik.

## Zobacz także

* Klasa [ObjectExt](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)