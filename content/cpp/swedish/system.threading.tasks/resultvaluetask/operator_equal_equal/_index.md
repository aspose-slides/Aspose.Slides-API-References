---
title: operator==()
second_title: Aspose.Slides för C++ API-referens
description: Likhetsoperator för ResultValueTask.
type: docs
weight: 131
url: /sv/system.threading.tasks/resultvaluetask/operator_equal_equal/
---
## ResultValueTask::operator==(const ResultValueTask\&) const metod

Likhetsoperator för [ResultValueTask](../).

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::operator==(const ResultValueTask &other) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | const [ResultValueTask](../)\& | Den andra [ResultValueTask](../) att jämföra med denna instans. |

### Returvärde

bool True om båda uppgifterna har samma resultatvärde eller refererar till samma underliggande uppgift; annars, false.
## Anmärkningar

Om någon av instanserna innehåller ett direkt resultatvärde jämförs resultaten direkt. Annars jämförs pekarna till den underliggande uppgiften.
## Se även

* Klass [ResultValueTask](../)
* Namnrymd [System::Threading::Tasks](../../)
* Bibliotek [Aspose.Slides](../../../)