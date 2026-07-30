---
title: Timer()
second_title: Riferimento API Aspose.Slides per C++
description: Costruttore.
type: docs
weight: 1
url: /it/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) costruttore


Costruttore.

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Funzione da chiamare dal timer. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) costruttore


Costruttore.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Funzione da chiamare dal timer. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argomento della funzione di callback. |
| dueTime | **int64_t** | [Timeout](../../timeout/) prima della prima invocazione della funzione di callback, in millisecondi; i valori negativi non programmano il timer dopo la creazione, quindi può essere rischedulato in seguito. |
| period | **int64_t** | [Timeout](../../timeout/) tra le invocazioni consecutive della funzione di callback, in millisecondi; valori non positivi significano che il timer dovrebbe essere eseguito solo una volta. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) costruttore


Costruttore.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Funzione da chiamare dal timer. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argomento della funzione di callback. |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) prima della prima invocazione della funzione di callback; i valori negativi non programmano il timer dopo la creazione, quindi può essere rischedulato in seguito. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) tra le invocazioni consecutive della funzione di callback; valori non positivi significano che il timer dovrebbe essere eseguito solo una volta. |

## Vedi anche

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Timer](../)
* Classe [Object](../../../system/object/)
* Classe [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Libreria [Aspose.Slides](../../../)