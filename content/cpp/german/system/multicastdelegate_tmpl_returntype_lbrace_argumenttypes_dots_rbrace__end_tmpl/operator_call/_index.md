---
title: operator()()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft alle aktuell in der Delegaten-Sammlung vorhandenen Delegaten auf. Delegaten werden in derselben Reihenfolge aufgerufen, in der sie der Sammlung hinzugefügt wurden. Der Operator blockiert, während die Delegaten ausgeführt werden.
type: docs
weight: 235
url: /de/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/operator_call/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes...) const Methode

Ruft alle aktuell in der Delegaten-Sammlung vorhandenen Delegaten auf. Delegaten werden in derselben Reihenfolge aufgerufen, in der sie der Sammlung hinzugefügt wurden. Der Operator blockiert, während die Delegaten ausgeführt werden.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes... args) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| args | ArgumentTypes... | Argumente, die an die aufzurufenden Delegaten übergeben werden |

### Rückgabewert

Rückgabewert des zuletzt aufgerufenen Delegaten

## Siehe auch

* Klasse [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)