---
title: MakeScopeGuard()
second_title: Aspose.Slides dla C++ API Reference
description: Funkcja fabryczna, która tworzy instancje klasy ScopedGuard.
type: docs
weight: 2809
url: /pl/system/makescopeguard/
---
## System::MakeScopeGuard(F) funkcja


Funkcja fabryczna, która tworzy instancje klasy ScopedGuard.

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| The | typ obiektu funkcyjnego, który ma zostać wywołany przez skonstruowany obiekt ScopedGuard |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| f | F | Obiekt funkcyjny przekazywany do konstruktora klasy ScopedGuard. |

### Wartość zwracana

Nowa instancja klasy ScopedGuard

## Zobacz także

* Struktura [ScopeGuard](../scopeguard/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)