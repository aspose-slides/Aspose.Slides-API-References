---
title: ScopeGuard
second_title: Aspose.Slides voor C++ API-referentie
description: De serviceklasse die diensten levert voor het uitvoeren van een specifiek functieobject wanneer een instantie van de klasse buiten het bereik valt.
type: docs
weight: 1886
url: /nl/system/scopeguard/
---
## ScopeGuard struct


De serviceklasse die diensten levert voor het uitvoeren van een specifiek functieobject wanneer een instantie van de klasse buiten het bereik valt.

```cpp
template<typename F>class ScopeGuard
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| F | Het type van het functieobject dat wordt aangeroepen door de instanties van de ScopedGuard klasse |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [Disable](./disable/)() | Schakelt de guard-aanroep uit. |
| [ScopeGuard](./scopeguard/)(F) | Construeert een instantie die is ingesteld om het opgegeven functieobject aan te roepen. |
| [~ScopeGuard](./~scopeguard/)() | Roep het functieobject aan dat aan de constructor is doorgegeven. |

## Zie ook

* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)