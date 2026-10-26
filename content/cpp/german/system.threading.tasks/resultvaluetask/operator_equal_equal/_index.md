---
title: operator==()
second_title: Aspose.Slides für C++ API Referenz
description: Gleichheitsoperator für ResultValueTask.
type: docs
weight: 131
url: /de/system.threading.tasks/resultvaluetask/operator_equal_equal/
---
## ResultValueTask::operator==(const ResultValueTask\&) const Methode

Gleichheitsoperator für [ResultValueTask](../).

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::operator==(const ResultValueTask &other) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const [ResultValueTask](../)\& | Das andere [ResultValueTask](../) zum Vergleich mit dieser Instanz. |

### Rückgabewert

bool True, wenn beide Tasks den gleichen Ergebniswert haben oder auf dieselbe zugrunde liegende Task verweisen; andernfalls false.

## Bemerkungen

Wenn eine der Instanzen einen direkten Ergebniswert enthält, werden die Ergebnisse direkt verglichen. Andernfalls werden die Zeiger auf die zugrunde liegenden Tasks verglichen.

## Siehe auch

* Klasse [ResultValueTask](../)
* Namensraum [System::Threading::Tasks](../../)
* Bibliothek [Aspose.Slides](../../../)