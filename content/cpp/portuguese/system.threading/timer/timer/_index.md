---
title: Timer()
second_title: Referência da API Aspose.Slides para C++
description: Construtor.
type: docs
weight: 1
url: /pt/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) construtor

Construtor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Função a ser chamada pelo timer. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) construtor

Construtor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Função a ser chamada pelo timer. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argumento da função de retorno de chamada. |
| dueTime | **int64_t** | [Timeout](../../timeout/) antes da primeira invocação da função de retorno de chamada, em milissegundos; valores negativos não agendam o timer após a criação, permitindo que ele seja reprogramado posteriormente. |
| period | **int64_t** | [Timeout](../../timeout/) entre invocações consecutivas da função de retorno de chamada, em milissegundos; valores não positivos indicam que o timer deve ser executado apenas uma vez. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) construtor

Construtor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Função a ser chamada pelo timer. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argumento da função de retorno de chamada. |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) antes da primeira invocação da função de retorno de chamada; valores negativos não agendam o timer após a criação, permitindo que ele seja reprogramado posteriormente. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) entre invocações consecutivas da função de retorno de chamada; valores não positivos indicam que o timer deve ser executado apenas uma vez. |

## Veja Também

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Timer](../)
* Classe [Object](../../../system/object/)
* Classe [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)