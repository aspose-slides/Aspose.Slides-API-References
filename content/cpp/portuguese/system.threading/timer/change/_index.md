---
title: Change()
second_title: Referência da API Aspose.Slides for C++
description: Reagenda ou cancela o temporizador.
type: docs
weight: 14
url: /pt/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) método

Reagenda ou cancela o temporizador.

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dueTime | **int64_t** | [Timeout](../../timeout/) antes da próxima invocação da função de retorno de chamada, em milissegundos; valores negativos cancelam o temporizador mesmo se ele estiver programado. |
| period | **int64_t** | [Timeout](../../timeout/) entre invocações consecutivas da função de retorno de chamada, em milissegundos; valores não positivos indicam que o temporizador deve ser executado apenas uma vez. |

## Timer::Change(System::TimeSpan, System::TimeSpan) método

Reagenda ou cancela o temporizador.

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) antes da próxima invocação da função de retorno de chamada; valores negativos cancelam o temporizador mesmo se ele estiver programado. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) entre invocações consecutivas da função de retorno de chamada; valores não positivos indicam que o temporizador deve ser executado apenas uma vez. |

## Ver Também

* Classe [Timer](../)
* Classe [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)