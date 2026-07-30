---
title: MakeScopeGuard()
second_title: Aspose.Slides pro C++ API Reference
description: Tovární funkce, která vytváří instance třídy ScopedGuard.
type: docs
weight: 2809
url: /cs/system/makescopeguard/
---
## System::MakeScopeGuard(F) function

Tovární funkce, která vytváří instance třídy ScopedGuard.

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```

### Template parameters

| Parametr | Popis |
| --- | --- |
| The | typ objektu funkce, který bude vyvolán konstruovaným objektem ScopedGuard |

### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| f | F | Objekt funkce, který se předá konstruktoru třídy ScopedGuard. |

### Return Value

Nová instance třídy ScopedGuard

## See Also

* Struktura [ScopeGuard](../scopeguard/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)