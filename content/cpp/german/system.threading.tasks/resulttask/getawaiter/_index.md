---
title: GetAwaiter()
second_title: Aspose.Slides für C++ API-Referenz
description: Erhält einen Awaiter für diese ResultTask zur Verwendung mit Await.
type: docs
weight: 53
url: /de/system.threading.tasks/resulttask/getawaiter/
---
## ResultTask::GetAwaiter() const Methode

Erhält einen Awaiter für diese ResultTask zur Verwendung mit Await.

```cpp
Runtime::CompilerServices::ResultTaskAwaiter<T> System::Threading::Tasks::ResultTask<T>::GetAwaiter() const
```

### Rückgabewert

Runtime::CompilerServices::ResultTaskAwaiter<T> Eine Awaiter-Instanz, die das Ergebnis zurückgibt

## Anmerkungen

Wenn gewartet, wird die Coroutine mit dem Ergebniswert fortgesetzt.

## Siehe auch

* Klasse [ResultTaskAwaiter](../../../system.runtime.compilerservices/resulttaskawaiter/)
* Klasse [ResultTask](../)
* Namensraum [System::Threading::Tasks](../../)
* Bibliothek [Aspose.Slides](../../../)