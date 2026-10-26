---
title: MakeScopeGuard()
second_title: Aspose.Slides voor C++ API-referentie
description: Een fabriekfunctie die instanties van de ScopedGuard-klasse maakt.
type: docs
weight: 2809
url: /nl/system/makescopeguard/
---
## System::MakeScopeGuard(F) functie

Een fabriekfunctie die instanties van de ScopedGuard-klasse maakt.

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| The | type van het functie-object dat wordt aangeroepen door het geconstrueerde ScopedGuard-object |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| f | F | Het functie-object dat moet worden doorgegeven aan de constructor van de ScopedGuard-klasse. |

### Retourwaarde

Een nieuwe instantie van de ScopedGuard-klasse

## Zie ook

* Struct [ScopeGuard](../scopeguard/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)