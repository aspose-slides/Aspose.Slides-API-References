---
title: Change()
second_title: Referencia de la API de Aspose.Slides para C++
description: Reprograma o cancela el temporizador.
type: docs
weight: 14
url: /es/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) método

Reprograma o cancela el temporizador.

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dueTime | **int64_t** | [Timeout](../../timeout/) antes de la siguiente invocación de la función de devolución de llamada, en milisegundos; los valores negativos cancelan el temporizador incluso si estaba programado. |
| period | **int64_t** | [Timeout](../../timeout/) entre invocaciones consecutivas de la función de devolución de llamada, en milisegundos; los valores no positivos indican que el temporizador sólo debe ejecutarse una vez. |

## Timer::Change(System::TimeSpan, System::TimeSpan) método

Reprograma o cancela el temporizador.

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) antes de la siguiente invocación de la función de devolución de llamada; los valores negativos cancelan el temporizador incluso si estaba programado. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) entre invocaciones consecutivas de la función de devolución de llamada; los valores no positivos indican que el temporizador sólo debe ejecutarse una vez. |

## Ver también

* Clase [Timer](../)
* Clase [TimeSpan](../../../system/timespan/)
* Espacio de nombres [System::Threading](../../)
* Biblioteca [Aspose.Slides](../../../)