---
title: CoalesceAssign()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Implementace překladu operátoru '??='.
type: docs
weight: 183
url: /cs/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign(T0\&, T1) metoda

Implementace překladu operátoru '??='.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::CoalesceAssign(T0 &value, T1 func) -> T0 &
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T0 | typ hodnoty LHS. |
| T1 | Typ lambda zapouzdřujícího výraz RHS. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | T0\& | Hodnota LHS. |
| func | T1 | Výraz RHS. |

### Návratová hodnota

Pokud hodnota LHS není null, vrátí LHS, jinak vypočítá výraz RHS a vrátí výsledek.

## Viz také

* Třída [ObjectExt](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)