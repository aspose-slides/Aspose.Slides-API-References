---
title: CoalesceInternal()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Implementace překladu operátoru '??' pro typy, které nejsou nullable. Přetížení pro případ, že RT2 lze převést na RT1.
type: docs
weight: 157
url: /cs/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal(RT1, F) metoda

Implementace překladu operátoru '??' pro typy, které nejsou nullable. Přetížení pro případ, že RT2 lze převést na RT1.

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T0 | Typ hodnoty LHS. |
| T1 | Typ lambda, který zapouzdřuje výraz RHS. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | RT1 | Hodnota LHS. |
| func | F | Výraz RHS. |

### Návratová hodnota

Pokud hodnota LHS není null, vrátí LHS, jinak vypočítá výraz RHS a vrátí výsledek.

## Viz také

* Třída [ObjectExt](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)