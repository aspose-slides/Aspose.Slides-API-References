---
title: Cancel()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Komunikuje żądanie anulowania.
type: docs
weight: 40
url: /pl/system.threading/cancellationtokensource/cancel/
---
## CancellationTokenSource::Cancel() metoda

Komunikuje żądanie anulowania.

```cpp
void System::Threading::CancellationTokenSource::Cancel()
```

## Uwagi

Wszystkie zarejestrowane wywołania zwrotne zostaną wywołane.

Kolejne wywołania [get_IsCancellationRequested()](../get_iscancellationrequested/) zwrócą true.

Wywołania zwrotne są wykonywane synchronicznie podczas tego wywołania.

## Zobacz także

* Klasa [CancellationTokenSource](../)
* Przestrzeń nazw [System::Threading](../../)
* Biblioteka [Aspose.Slides](../../../)