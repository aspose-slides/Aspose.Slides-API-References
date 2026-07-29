---
title: ScopeGuard
second_title: Aspose.Slides för C++ API-referens
description: Tjänsteklassen som tillhandahåller tjänster för att köra ett specifikt funktionobjekt när en instans av klassen går ur scope.
type: docs
weight: 1886
url: /sv/system/scopeguard/
---
## ScopeGuard struct

Tjänsteklassen som tillhandahåller tjänster för att köra ett specifikt funktionobjekt när en instans av klassen går ur scope.

```cpp
template<typename F>class ScopeGuard
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| F | Typen av funktionobjektet som anropas av instanserna av ScopedGuard-klassen |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [Disable](./disable/)() | Inaktiverar guard-anropet. |
|  [ScopeGuard](./scopeguard/)(F) | Skapar en instans som är konfigurerad för att anropa det angivna funktionobjektet. |
|  [~ScopeGuard](./~scopeguard/)() | Anropar funktionobjektet som skickades till konstruktorn. |

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)