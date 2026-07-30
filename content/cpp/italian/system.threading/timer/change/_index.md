---
title: Change()
second_title: Aspose.Slides per il riferimento API di C++
description: Riprogramma o annulla il timer.
type: docs
weight: 14
url: /it/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) metodo

Riprogramma o annulla il timer.

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dueTime | **int64_t** | [Timeout](../../timeout/) prima della prossima invocazione della funzione di callback, in millisecondi; i valori negativi annullano il timer anche se era stato programmato. |
| period | **int64_t** | [Timeout](../../timeout/) tra le invocazioni consecutive della funzione di callback, in millisecondi; i valori non positivi indicano che il timer deve essere eseguito una sola volta. |

## Timer::Change(System::TimeSpan, System::TimeSpan) metodo

Riprogramma o annulla il timer.

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) prima della prossima invocazione della funzione di callback; i valori negativi annullano il timer anche se era stato programmato. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) tra le invocazioni consecutive della funzione di callback; i valori non positivi indicano che il timer deve essere eseguito una sola volta. |

## Vedi anche

* Classe [Timer](../)
* Classe [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Libreria [Aspose.Slides](../../../)