---
title: AsTask()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert dieses ResultValueTask in einen gemeinsamen Zeiger auf ResultTask<T>.
type: docs
weight: 79
url: /de/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask() const method

Converts this [ResultValueTask](../) to a shared pointer to ResultTask<T>.

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```

### Rückgabewert

RTaskPtr<T> Ein gemeinsamer Zeiger auf ein ResultTask<T>, das diese Operation darstellt.

## Bemerkungen

Wenn das [ResultValueTask](../) ein direktes Ergebnis enthält, wird ein abgeschlossener Task mit diesem Ergebnis erstellt. Wenn es einen Task enthält, gibt es einen gemeinsamen Zeiger auf diesen Task zurück.

## Siehe auch

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Klasse [ResultValueTask](../)
* Namensraum [System::Threading::Tasks](../../)
* Bibliothek [Aspose.Slides](../../../)