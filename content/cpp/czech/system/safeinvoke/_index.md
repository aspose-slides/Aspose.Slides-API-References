---
title: SafeInvoke()
second_title: Aspose.Slides pro C++ referenci API
description: Implementace překladu operátoru '?.'.
type: docs
weight: 2653
url: /cs/system/safeinvoke/
---
## System::SafeInvoke(T0\&&, T1\&&) funkce

Implementace překladu operátoru '?.'.

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T0 | typ výrazu. |
| T1 | Typ lambda zapouzdřujícího výraz 'WhenTrue'. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| expr | T0\&& | hodnota výrazu. |
| func | T1\&& | výraz 'WhenTrue' svázaný s funktorem. |

### Návratová hodnota

Pokud hodnota expr není null, vrátí výsledek volání func s touto hodnotou jako prvním argumentem, jinak vrátí null.

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)