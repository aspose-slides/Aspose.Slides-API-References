---
title: MakeScopeGuard()
second_title: Aspose.Slides för C++ API-referens
description: En fabrikfunktion som skapar instanser av klassen ScopedGuard.
type: docs
weight: 2809
url: /sv/system/makescopeguard/
---
## System::MakeScopeGuard(F) funktion


En fabrikfunktion som skapar instanser av klassen ScopedGuard.

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Den | typ av funktionsobjektet som ska anropas av det konstruerade ScopedGuard-objektet |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| f | F | Funktionsobjektet som ska skickas till konstruktor för klassen ScopedGuard. |

### Returvärde

En ny instans av klassen ScopedGuard

## Se även

* Struktur [ScopeGuard](../scopeguard/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)