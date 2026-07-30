---
title: ScopeGuard
second_title: Aspose.Slides pro referenci API C++
description: Třída služby, která poskytuje služby pro spuštění konkrétního funkčního objektu, když instance třídy opustí rozsah.
type: docs
weight: 1886
url: /cs/system/scopeguard/
---
## ScopeGuard struct

Třída služby, která poskytuje služby pro spuštění konkrétního funkčního objektu, když instance třídy opustí rozsah.

```cpp
template<typename F>class ScopeGuard
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| F | Typ funkčního objektu, který je volán instancemi třídy ScopedGuard |

## Metody

| Metoda | Popis |
| --- | --- |
| void [Disable](./disable/)() | Zakáže volání strážce. |
| [ScopeGuard](./scopeguard/)(F) | Vytvoří instanci, která je připravena k volání zadaného funkčního objektu. |
| [~ScopeGuard](./~scopeguard/)() | Volá funkční objekt předaný konstruktoru. |

## Viz také

* jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)