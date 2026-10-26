---
title: CoalesceInternal()
second_title: Aspose.Slides dla C++ Referencja API
description: Implementacja translacji operatora '??' dla typów niepustych. Przeciążenie dla przypadku, gdy RT2 jest konwertowalny na RT1.
type: docs
weight: 157
url: /pl/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal(RT1, F) metoda

Implementacja translacji operatora '??' dla typów niepustych. Przeciążenie dla przypadku, gdy RT2 jest konwertowalny na RT1.

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T0 | Typ wartości LHS. |
| T1 | Typ lambdy enkapsulującej wyrażenie RHS. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | RT1 | wartość LHS. |
| func | F | wyrażenie RHS. |

### Wartość zwracana

Jeśli wartość LHS nie jest nullem, zwraca LHS, w przeciwnym razie oblicza wyrażenie RHS i zwraca wynik.

## Zobacz także

* Klasa [ObjectExt](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)