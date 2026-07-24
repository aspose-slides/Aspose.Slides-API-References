---
title: FromCanceled()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine Aufgabe, die aufgrund einer Abbruchanforderung mit dem angegebenen Token abgeschlossen wurde.
type: docs
weight: 118
url: /de/system.threading.tasks/fromcanceled/
---
## System::Threading::Tasks::FromCanceled(const CancellationToken\&) Funktion


Erstellt eine Aufgabe, die aufgrund einer Abbruchanforderung mit dem angegebenen Token abgeschlossen wurde.

```cpp
TaskPtr System::Threading::Tasks::FromCanceled(const CancellationToken &cancellationToken)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Das Abbruch-Token, das dazu führte, dass die Aufgabe abgebrochen wurde. |

### Rückgabewert

Eine abgebrochene Aufgabe.

## Siehe auch

* Typedef [TaskPtr](../../system/taskptr/)
* Klasse [CancellationToken](../../system.threading/cancellationtoken/)
* Namensraum [System::Threading::Tasks](../)
* Bibliothek [Aspose.Slides](../../)