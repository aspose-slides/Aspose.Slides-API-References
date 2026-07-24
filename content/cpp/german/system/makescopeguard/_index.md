---
title: MakeScopeGuard()
second_title: Aspose.Slides für C++ API-Referenz
description: Eine Fabrikfunktion, die Instanzen der Klasse ScopedGuard erstellt.
type: docs
weight: 2809
url: /de/system/makescopeguard/
---
## System::MakeScopeGuard(F) Funktion


Eine Fabrikfunktion, die Instanzen der Klasse ScopedGuard erstellt.

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| The | Typ des Funktionsobjekts, das vom konstruierten ScopedGuard-Objekt aufgerufen wird |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| f | F | Das Funktionsobjekt, das an den Konstruktor der Klasse ScopedGuard übergeben wird |

### Rückgabewert

Eine neue Instanz der Klasse ScopedGuard

## Siehe auch

* Struct [ScopeGuard](../scopeguard/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)