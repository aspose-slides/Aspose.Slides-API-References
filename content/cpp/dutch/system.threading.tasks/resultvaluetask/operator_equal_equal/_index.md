---
title: operator==()
second_title: Aspose.Slides voor C++ API-referentie
description: Gelijkheidsoperator voor ResultValueTask.
type: docs
weight: 131
url: /nl/system.threading.tasks/resultvaluetask/operator_equal_equal/
---
## ResultValueTask::operator==(const ResultValueTask\&) const methode

Gelijkheidsoperator voor [ResultValueTask](../).

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::operator==(const ResultValueTask &other) const
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | const [ResultValueTask](../)\& | De andere [ResultValueTask](../) om te vergelijken met deze instantie. |

### Retourwaarde

bool True als beide taken dezelfde resultaatwaarde hebben of naar dezelfde onderliggende taak verwijzen; anders false.

## Opmerkingen

Als een van de instanties een directe resultaatwaarde bevat, vergelijkt het de resultaten direct. Anders vergelijkt het de onderliggende taakpointers.

## Zie ook

* Klasse [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Bibliotheek [Aspose.Slides](../../../)